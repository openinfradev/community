# Development Guide

HANU Community 개발자 여러분! HANU는 모든 소스 코드 뿐만 아니라 전체 개발 과정을 자세히 문서화하여 GitHub에 공개하고 있습니다. 누구나 HANU에 관심이 있는 분은 아래 문서들을 참고하여 개발에 참여하여 자신의 역량을 쌓을 수 있을 뿐만 아니라 한국의 오픈소스 생태계에 기여할 수 있습니다. HANU는 한국의 오픈소스 개발자 분들과 함께합니다!

HANU Community에는 여러개의 Project가 있으며 모두 공통적으로 아래의 개발 절차를 준수합니다.  

## How to Build

HANU Community의 주오 Project는 Docker 기반 빌드 환경을 제공합니다. 

다음 페이지에 Project Build를 위한 공통적으로 설치가 요구되는 사항을 정리하였으니 참고하세요. [How to Build](./build.md)

## How to Test

HANU Community의 주요 Project는 다음과 같은 Test를 통해 개발/배포합니다. 기여를 준비하는 오픈소스 개발자 분들은 자신의 개발 결과가 HANU의 Project에 이상없이 반영할 수 있을지에 대해 Unit Test와 Integration Test를 통해 확인할 수 있습니다. 

HANU의 Project는 Master Branch의 안정성 유지를 위해 Unit Test, Integration Test, End-to-End Test에 통과한 Pull Request만을 Merge합니다.

* Unit Test
* Integration Test
* End-to-End Test
* Conformance Test

각 Test의 절차 및 요구사항을 다음 페이지에서 자세히 설명합니다. : [Testing Guide](test.md)




## 개발 / 기여 프로세스

HANU의 각 Project에 직접 개발에 참여하고 기여하기 위해서는 기본적으로 아래의 내용에 익숙해지시기 바랍니다. 

* [CONTRIBUTING](../contributing/README.md) : HANU에 기여하기 위한 방법
* [Pull Request](../contributing/pull-requests.md) : Pull Request 절차
* []

HANU 프로젝트에 코드를 개발하고 제공하는 프로세스

* **Contributor Guide**
  ([여기에서 시작하십시오] (/ tributors / guide / README)
.md)) Kubernetes에 기여하는 방법에 대해 알아보기

* **GitHub Issues** : 들어오는 문제가 심사되는 방식.

* **Pull Request Process** : 풀 요청이 언제, 왜 닫힙니다.

* **Getting Recent Builds** : CI를 통과 한 최신 빌드를 포함하여 최근 빌드를 얻는 방법.

* **Automated Tools** : github 리포지토리에서 실행중인 자동화에 대한 설명입니다.


## 개발 환경 설정, 코딩 및 디버깅

* **개발 안내서** : 개발 환경 설정.

* *Testing** : 개발 샌드 박스에서 단위, 통합 및 엔드 투 엔드 테스트를 실행하는 방법.

* **Logging Conventions** : klog 레벨.

* **Coding Conventions** : contributor를 위한 코딩 스타일 조언.

* **문서 규약** : 기고자에게 문서 스타일 조언.

* **로컬환경에서의 실행** : contributor의 개발 환경에서 실행 방법

## Operation 가이드
* Logging and Monitoring
* Maintenance, Failure and Debugging
* (Network) Trouble Shooting
* Backup and Recovery
* Configuration and Upgrade

## Repo 운영 프로세스
Repogitory 운영 프로세스 상세 내용

HANU Community에서의 개발 과정에 문의나 의견이 있을 경우 [Issue](https://github.com/openinfradev/community-draft/issues/new)를 생성해주세요. 
