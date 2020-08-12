# Coding Conversion

**Table of Contents**




## Overview



## Coding conversion and Running the Tests

There are a variety of ways to run e2e tests, but we aim to decrease the number
of ways to run e2e tests to a canonical way: `kubetest`.

For information on installing `kubetest`, please see the
[installation section](https://github.com/kubernetes/test-infra/tree/master/kubetest#installation) of the
[Kubetest project documentation](https://github.com/kubernetes/test-infra/tree/master/kubetest).

You can run an end-to-end test which will bring up a master and nodes, perform
some tests, and then tear everything down. Make sure you have followed the
getting started steps for your chosen cloud platform (which might involve
changing the --provider flag value to something other than "gce").

You can quickly recompile the e2e testing framework via `go install ./test/e2e`.
This will not do anything besides allow you to verify that the go code compiles.
If you want to run your e2e testing framework without re-provisioning the e2e setup,
you can do so via `make WHAT=test/e2e/e2e.test`, and then re-running the ginkgo tests.

To build Kubernetes, up a cluster, run tests, and tear everything down, use:

```sh
kubetest --build --up --test --down
```

If you'd like to just perform one of these steps, here are some examples:

```sh
# Build binaries for testing
kubetest --build

# Create a fresh cluster.  Deletes a cluster first, if it exists
kubetest --up

# Run all tests
kubetest --test

# Run tests matching the regex "\[Feature:Performance\]" against a local cluster
# Specify "--provider=local" flag when running the tests locally
kubetest --test --test_args="--ginkgo.focus=\[Feature:Performance\]" --provider=local

# Conversely, exclude tests that match the regex "Pods.*env"
kubetest --test --test_args="--ginkgo.skip=Pods.*env"

# Run tests in parallel, skip any that must be run serially
GINKGO_PARALLEL=y kubetest --test --test_args="--ginkgo.skip=\[Serial\]"

# Run tests in parallel, skip any that must be run serially and keep the test namespace if test failed
GINKGO_PARALLEL=y kubetest --test --test_args="--ginkgo.skip=\[Serial\] --delete-namespace-on-failure=false"

# Flags can be combined, and their actions will take place in this order:
# --build, --up, --test, --down
#
# You can also specify an alternative provider, such as 'aws'
#
# e.g.:
kubetest --provider=aws --build --up --test --down
```

The tests are built into a single binary which can be used to deploy a
Kubernetes system or run tests against an already-deployed Kubernetes system.
See `kubetest --help` for more options, such as reusing an existing cluster.

### Cleaning up



## Advanced testing

### Extracting a specific version of Kubernetes



### Version-skewed and upgrade testing


#### Test jobs naming convention


### Viper configuration and hierarchichal test parameters.


### Conformance tests


## Continuous Integration



### What is CI?



### What runs in CI?



#### Non-default tests



### The PR-builder



### Adding a test to CI



**NOTE:** 

### Moving a test out of CI


## Performance Evaluation



## One More Thing



**HAPPY Coding!**

