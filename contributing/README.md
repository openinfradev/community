# How to Contribute

HANU Community에 오신 모든 분들을 열렬히 환영합니다!!! :DDDDD

HANU는 모든 소스 코드와 문서를 완전히 공개하고 커뮤니티 구성원이 협업하여 개발하는 오픈소스 개발 방식을 따릅니다. 여러분의 소중한 기여로 HANU Community의 Project는 성장할 수 있습니다. 

여기서는 HANU Community에 기여하기 위한 방법을 자세히 설명합니다. 

- [How to Contribute](#how-to-contribute)
  - [Prerequisites](#prerequisites)
    - [Sign the CLA](#sign-the-cla)
    - [Code of Conduct](#code-of-conduct)
  - [개발 환경 구축](#개발-환경-구축)
  - [GitHub Workflow](#github-workflow)
  - [Testing](#testing)
  - [Pull Request 프로세스](#pull-request-프로세스)
  - [Code Review](#code-review)
  - [Documentation](#documentation)
  

## Prerequisites

HANU Community에 기여하기 전에 몇가지 확인해야 할 사항들이 있습니다. 

### Sign the CLA

HANU Community는 예기치 않은 법적 문제를 방지하기 위해 기여자에게 [Contributor License Agreement](../CLA.md)의 서명을 받고 있습니다. 기여자가 CLA에 서명함으로 HANU Community의 모든 Project는 누구나 법적인 문제 없이 자유롭게 사용하고 배포할 수 있게 됩니다.  

### Code of Conduct

HANU Community는 모든 구성원을 환영하고 존중합니다. 이러한 문화와 환경이 지속되기 위해 모든 구성원은 [Code of Conduct / 행동 강령](../code-of-conduct.md)을 준수해야 합니다. 꼭 주의 깊게 읽고 따라주시기 바랍니다. 

## 개발 환경 구축

[Development Guide](../developing/README.md)에서는 개발 환경 구축, 빌드, 테스트 등 개발에 참여하기 위해 필요한 내용을 자세히 안내합니다.


## GitHub Workflow

HANU Community는 GitHub Workflow에 따라 기여를 제출하고 검토 및 Merge합니다. 

다음 페이지에서 HANU Community의 [GitHub Workflow](github-workflow.md)를 확인하세요. 


## Testing

HANU Community의 신뢰성과 안정성을 위해 모든 기여자는 기여를 제출하기 전에 Test를 수행해야 합니다. HANU Community는 다음과 같은 형태의 Test를 수행하고 있습니다. 

* Unit Test
* Integration Test
* End-to-end ("e2e") Test
  
Test와 관련한 자세한 사항은 다음 페이지를 참고하세요. : [Testing Guide](../developing/test.md) 


## Pull Request 프로세스

HANU Community에 Pull Request를 제출하면 어떤일이 벌어질까요? 

어떤 Pull Request가 쉽게 merge가 될 수 있을까요? 

이에 대한 자세한 설명을 다음 페이지에서 참고하세요. : [Pull Request 프로세스](pull-requests.md)


## Code Review

Code Review는 Code의 가독성과 품질을 높여서 신뢰할 수 있는 HANU Community의 Project가 되기 위해 꼭 필요한 절차입니다.  

Code Review 과정의 절차와 역할은 각각 다음 페이지에서 확인하실 수 있습니다. 

* 절차 : [Pull Request 프로세스](pull-requests.md)
* 역할 : [Membership](../governance/membership.md) 

Reviewer에게 좋은 Review 결과를 얻기 위해서는 다음 사항을 유념하세요. 

* [Coding Convention](../developing/coding-convention.md)을 따르세요.
* [Commit Message](https://chris.beams.io/posts/git-commit/)는 간단 명료하면서도 Reviewer가 변경 사항을 쉽게 이해할 수 있도록 충분한 정보를 포함하여 작성하세요.
* 변경 사항이 많다면 이를 논리적인 일련의 작은 패치로 나누어서 변경 사항을 이해하기 쉽게 만드세요.


## Documentation

> `need-to-improve` >
> * User Guide를 위한 웹사이트를 구축한다면, 문서화에 기여하는 방법을 여기에 추가해야함
> * 필요한 시점에 작성합니다. 

---

HANU Community에서의 기여 과정에 문의나 의견이 있을 경우 [Issue](https://github.com/openinfradev/community-draft/issues/new)를 생성해주세요. 
