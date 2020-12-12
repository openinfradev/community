# Membership

> `need-to-improve` 
> * 멤버쉽 어떻게 구성할지에 대한 결정 필요 
> * 참고 : https://github.com/kubernetes/community/blob/master/community-membership.md

**Note:** This document is in progress

HANU의 프로젝트에는 다음과 같은 역할의 참여자가 있습니다. 

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Member | 커뮤니티에 적극적인 기여| 2명의 Reviewer로부터 후원을 받은 적극적인 기여자 | GitHub org member |
| Reviewer | 다른 멤버의 기여 Review | 프로젝트 내 Review와 저작 이력이 풍부한 Member | [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file reviewer entry |
| Approver | 기여 수락에 대한 승인 | 경험이 풍부하고 적극적인 Reviewer | [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file approver entry |
| Project Owner | Project의 방향 및 우선순위 결정 | 프로젝트에 대한 책임과 탁월한 기술적 판단력이 입증된 자 | [sigs.yaml](https://github.com/kubernetes/community/blob/master/sigs.yaml) subproject [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file owners entry |

각 역할의 요구사항과 책임 및 권한은 다음과 같습니다. 

## Member

Member는 커뮤니티에 지속적으로 기여한 기여자입니다. Issue와 PR을 자신에게 assign할 수 있고, SIG에 참여할 수 있습니다. 

정의 : Member는 GitHub organization의 Member로 등록됩니다. 

### 요구사항
- Github 계정에서 [two-factor authentication](https://help.github.com/articles/about-two-factor-authentication) 활성화합니다.
- 프로젝트에 다음과 같은 형태의  기여를 합니다.
  - GitHub에서 PR 작성 또는 Review
  - GitHub에서 Issue 생성 또는 Comment 작성
  - SIG, Project 등 커뮤니티 내 토론 (미팅, Slack, 메일링 리스트 등)에 기여
메일링리스트 가입합니다.
- [contributor guide](https://github.com/kubernetes/community/blob/master/contributors/guide/README.md)숙독합니다.
- 하나 이상의 프로젝트에 적극적으로 기여합니다.
- 2명의 Reviewer로부터 후원을 받습니다.
  - 후원자는 예비 멤버와 긴밀하게 작업한 이력이 있어야 함. (예: code/design/proposal review, issue 조율 등)
  - 후원자는 여러 회사 출신이어야 함
- org repository에 "REQUEST: New membership for <your-GH-handle>"이라는 제목의 Issue를 생성합니다. (예: https://github.com/kubernetes/org/issues/new?template=membership.md&title=REQUEST%3A%20New%20membership%20for%20%3Cyour-GH-handle%3E)
  - 이때 후원자를 멘션표시(@mentioned) 합니다.
  - 체크리스트의 모든 항목을 완료합니다. ([preview the current version of the template](https://git.k8s.io/org/.github/ISSUE_TEMPLATE/membership.md))
- 후원자(Reviewer)에게 +1을 체크하도록 요청합니다. 
- 후원자 응답이 완료되면 GitHub 관리팀 (예: [Kubernetes GitHub Admin team](https://github.com/kubernetes/community/blob/master/github-management/README.md#github-administration-team))이 검토하고, 누락된 정보가 있으면 보완을 요청합니다. 

### 책임과 특권

- 할당된 Issue와 PR에 대응합니다. 
- 그들이 기여한 코드의 active owner입니다.
  - 코드는 잘 테스트되어야 합니다.
  - 테스트는 항상 통과되어야 합니다.
  - 버그나 이슈를 해결합니다. 
- 멤버는 오픈된 PR에 대해  /lgtm를 할 수 있습니다. 
- Issue나 PR에 대해 할당될 수 있으며, 사람들은 멤버에게 /cd @username 하여 review 요청할 수 있습니다. 


## Reviewer


## Appoval


## Project Owner