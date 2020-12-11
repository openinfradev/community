Developing on HANU project
==============================

HANU 프로젝트는 오픈소스 프로젝트로 여러분의 기여와 의견을 적극적으로 환영합니다. :blush:

이 문서는 HANU Project의 개발 체계에 대해 설명합니다.

Github Issue 
------------
* Bug Report, Feature Request 는 모두 Github Issue로 등록되어야 합니다.
* Issue 등록 시, 제공되는 Issue Template에 맞게 정보를 작성하지 않으면 정보 부족으로 Issue가 Closed 될 수 있습니다.
* 채택된 Issue는 Label이 추가됩니다.

Code Contribution
-----------------
> Note: 먼저 Github Issue로 등록되어 Labeling 된 이후, 아래 단계를 시작합니다.
> Issue가 없는 PR을 Reject 됩니다.

1. Origin Repo를 Fork하여 개발합니다. 참고: [fork-a-repo guide](https://help.github.com/articles/fork-a-repo)
2. forked repository에서 개발이 완료되면, Pull Request로 Merge 요청을 합니다. 참고: [submit a pull request](https://help.github.com/articles/using-pull-requests)
3. PR이 생성되면 CI pipeline(github action, jenkins pipeline 등)이 실행됩니다. CI Pipeline 실패 시, 문제를 수정하여 commit 해야합니다.
4. CI Pipeline이 통과되면, 1명 이상의 review approval을 받아 Merge됩니다.

CI Pipeline
-----------
HANU Project에서는 github action과 jenkins를 사용하고 있습니다.

### Github Action
code build, unit test, docker image build & push 와 같은 대부분의 CI 작업을 커버하고 있습니다.

각 프로젝트의 .github/workflows 밑에서 파이프라인을 확인할 수 있습니다.

### Jenkins
[tacoplay](https://github.com/openinfradev/tacoplay) 프로젝트와 같이 인프라에 지속적으로 배포 테스트를 하는 경우에 사용합니다. 

현재 1개의 CI Pipeline이 있습니다.
- PR 생성 및 업데이트 시, CI용 인프라에 ansible playbook 배포 테스트 

Project Release
---------------
Release 주기는 아직 `미정`입니다.

Release는 Tag로 관리되며, Release Note로 변경사항을 확인할 수 있습니다.


개발 Agenda & 논의 사항 공유
-----------------------
Google Docs에 월 정기 회의 회의록을 공유합니다.

Slack Channel을 통해 실시간으로 소통할 수 있습니다.

