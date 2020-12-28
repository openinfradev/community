# Development Guide

HANU Community 개발자 여러분! 

HANU는 모든 소스 코드 뿐만 아니라 전체 개발 과정을 자세히 문서화하여 GitHub에 공개하고 있습니다. 누구나 HANU에 관심이 있는 분은 아래 문서들을 참고하여 개발에 참여하여 자신의 역량을 쌓을 수 있을 뿐만 아니라 한국의 오픈소스 생태계에 기여할 수 있습니다. HANU는 한국의 오픈소스 개발자 분들과 함께합니다!

HANU Community에는 여러개의 Project가 있으며 모두 공통적으로 아래의 개발 절차를 준수합니다.  

- [Development Guide](#development-guide)
  - [How to Build](#how-to-build)
  - [Testing Guide](#testing-guide)
  - [Coding Convention](#coding-convention)
  - [CI/CD](#cicd)
  - [Release](#release)

## How to Build

HANU Community의 주요 Project는 Docker 기반 빌드 환경을 제공합니다. 

다음 페이지에 Project Build를 위한 공통적으로 설치가 요구되는 사항을 정리하였으니 참고하세요. [How to Build](./build.md)

## Testing Guide

HANU Community의 주요 Project는 다음과 같은 Test를 통해 개발/배포합니다. 기여를 준비하는 오픈소스 개발자 분들은 자신의 개발 결과가 HANU의 Project에 이상없이 반영할 수 있을지에 대해 Unit Test와 Integration Test를 통해 확인할 수 있습니다. 

HANU의 Project는 Master Branch의 안정성 유지를 위해 Unit Test, Integration Test, End-to-End Test에 통과한 Pull Request만을 Merge합니다.

* Unit Test
* Integration Test
* End-to-End Test

각 Test의 절차 및 요구사항을 다음 페이지에서 자세히 설명합니다. : [Testing Guide](test.md)


## Coding Convention

HANU Community내 Project의 소스 코드 작성 시 준수해야 할 Coding Style 있습니다. HANU Project 소스 코드의 일관성과 가독성을 위해 기여자 분들은 가능한 이 Coding Convention을 따라주세요. : [Coding Convention](coding-convention.md)


## CI/CD

HANU Community는 Continuous Integration / Continuous Deployment를 위한 자동화 환경을 구축하고 있습니다. HANU의 CI/CD에 대한 자세한 사항은 다음 페이지를 참고하세요. : [CI/CD](ci-cd.md)


## Release

HANU Community내 Project의 Release 정책과 절차에 대한 자세한 내용은 다음 페이지를 참고하세요. : [Release](release.md)

---

HANU Community에서의 개발 과정에 문의나 의견이 있을 경우 [Issue](https://github.com/openinfradev/community/issues/new)를 생성해주세요. 
