# Testing guide

HANU Community의 주요 Project는 다음과 같은 Test를 통해 개발/배포합니다. 기여를 준비하는 오픈소스 개발자 분들은 자신의 개발 결과가 HANU의 Project에 이상없이 반영할 수 있을지에 대해 Unit Test와 Integration Test를 통해 확인할 수 있습니다. 

HANU의 Project는 Master Branch의 안정성 유지를 위해 Unit Test, Integration Test, End-to-End Test에 통과한 Pull Request만을 Merge합니다.

## Unit Test

Unit Test는 특정 모듈이 의도된 대로 정상적인 동작을 하는지 테스트 절차입니다. HANU Project의 모든 Package나 주요 파일은 Unit Test를 작성하고 수행해야 합니다. 

새로운 Package나 주요 기능을 추가한 경우 반드시 Unit Test에도 추가해야 합니다. 

> `need-to-improve` 다음 사항에 대한 확인 및 추가 작성이 필요합니다. 
> 
> * Unit Test 수행 환경 구축 
> * Unit Test 개발 가이드 작성
> * Unit Test 수행 방법 가이드 문서 작성
> 
> 가이드 문서는 다음 페이지를 참고할 수 있습니다.  : [#unit-tests](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-testing/testing.md#unit-tests)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

## Integration tests

Integration Test는 각각의 Package들이 상호작용하여 정상적인 동작을 하는지 테스트하는 절차입니다. Unit Test를 완료한 후에는 Integration Test를 수행하여 복잡한 상황에서 모든 기능이 정상적으로 수행하는지 확인합니다. 

Integration Test에 대한 방법은 다음과 같습니다. 


> `need-to-improve` 다음 사항에 대한 확인 및 추가 작성이 필요합니다. 
> 
> * Integration Test 수행 환경 구축
> * Integration Test 수행 방법 가이드 작성
> 
> 다음 페이지를 참고할 수 있습니다.  : [Integration tests](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-testing/integration-tests.md)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


## End-to-End tests

End-to-End Test (e2e)는 각 시스템 간 동작을 테스트하는 과정입니다. Unit Test와 Integration Test에 통과하였다고 해도 HANU와 같이 분산 환경에서의 여러 시스템이 맞물려서 동작하는 경우, e2e Test에서 문제가 발생하는 경우가 적지 않습니다. 

e2e Test를 통해 HANU Project의 일관되고 안정적인 동작을 보장할 수 있습니다.

e2e Test의 절차 및 방법은 다음과 같습니다. 



> `need-to-improve` 다음 사항에 대한 확인 및 추가 작성이 필요합니다. 
> 
> * e2e Test 수행 환경 구축
> * e2e Test 수행 방법 가이드 작성
> 
> 다음 페이지를 참고할 수 있습니다.  : [e2e tests](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-testing/e2e-tests.md)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

---
HANU Community에서의 Test 과정에 문의나 의견이 있을 경우 [Issue](https://github.com/openinfradev/community-draft/issues/new)를 생성해주세요. 

