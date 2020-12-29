# Membership
- [Membership](#membership)
  - [Member](#member)
  - [Contributor](#contributor)
    - [요구사항](#요구사항)
    - [책임과 권한](#책임과-권한)
  - [Committer](#committer)
    - [요구 사항](#요구-사항)
    - [책임과 권한](#책임과-권한-1)
  - [Maintainer](#maintainer)
    - [요구 사항](#요구-사항-1)
    - [책임과 권한](#책임과-권한-2)


HANU의 프로젝트에는 다음과 같은 역할의 참여자가 있습니다. 

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| [Member](#member) | HANU에 참여하는 전원 |   |
| [Contributor](#contributor) | 코드, 문서 등 Github repository에 직접적인 기여를 한 자| 프로젝트 내 Review와 저작 이력이 있는 Member | * 등록 방법 추가 필요 (예: [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file reviewer entry) |
| [Committer](#committer) | 코드에 대한 리뷰와 Merge 권한을 가진 자 | 경험이 풍부하고 적극적인 Contributor | * 등록 방법 추가 필요 (예: [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file approver entry) |
| [Maintainer](#maintainer) | 프로젝트에 대한 기술 지휘권을 가진 자 | 기술적 목표와 방향에 대한 깊은 이해| * 등록 방법 추가 필요 (예: [OWNERS](https://github.com/kubernetes/community/blob/master/contributors/guide/owners.md) file project owner entry) |
각 역할에 대한 요구사항, 책임 및 권한은 다음과 같습니다.  

## Member

HANU는 오픈소스의 협업과 공유 정신에 따라 누구든지 참여할 수 있으며, HANU의 행동 강령([Code of Conduct](../code-of-conduct.md))을 준수하는 모든 참여 인원은 HANU의 Member입니다. 

* Member는 HANU 내 여러 프로젝트의 사용자로서 프로젝트에 목적을 부여하고, 기능, 버그 리포트 등의 방법으로 피드백을 제공함으로써 프로젝트를 발전시키는 데 도움을 줄 수 있습니다. 
* 이처럼 Member는 HANU의 성장과 발전에 가장 중요한 구성원입니다. 

## Contributor

Contributor는 코드, 문서화 등의 방법으로 HANU에 지속해서 공헌한 기여자입니다. 
* Issue와 PR을 자신에게 Assign 할 수 있고, SIG에 참여할 수 있습니다. 
* Contributor는 는 GitHub organization의 Member로 등록됩니다. 

### 요구사항
- Github 계정에서 [two-factor authentication](https://help.github.com/articles/about-two-factor-authentication) 활성화합니다.
- 프로젝트에 다음과 같은 형태의  기여를 합니다.
  - GitHub에서 PR 작성 또는 Review
  - GitHub에서 Issue 생성 또는 Comment 작성
  - SIG, Project 등 커뮤니티 내 토론 (미팅, Slack, 메일링 리스트 등)에 기여
메일링리스트 가입합니다.
- [contributor guide](https://github.com/kubernetes/community/blob/master/contributors/guide/README.md)를 숙독합니다.
- 하나 이상의 프로젝트에 적극적으로 기여합니다.
- 2명의 Committer로부터 후원을 받습니다.
  - Committer인 후원자는 예비 Contributor와 긴밀하게 작업한 이력이 있어야 함. (예: code/design/proposal review, issue 조율 등)
  - 각 후원자는 다른 조직 소속이어야 함
- [community](https://github.com/openinfradev/community) repository에 "REQUEST: New membership for <your github account>"이라는 제목의 Issue를 생성합니다. (* issue template 신규 생성 필요 (예: [k8s issue tempalte](https://github.com/kubernetes/org/issues/new?template=membership.md&title=REQUEST%3A%20New%20membership%20for%20%3Cyour-GH-handle%3E)))
  - 이때 후원자를 멘션 표시(@mentioned) 합니다.
  - 체크리스트의 모든 항목을 완료합니다. (* 체크리스트 신규 생성 필요 (예: [preview the current version of the template](https://git.k8s.io/org/.github/ISSUE_TEMPLATE/membership.md)))
- 후원자에게 +1을 체크하도록 요청합니다. 
- 후원자 응답이 완료되면 GitHub 관리팀 (* HANU GitHub 관리 조직 생성 필요 - 예: [Kubernetes GitHub Admin team](https://github.com/kubernetes/community/blob/master/github-management/README.md#github-administration-team))이 검토하고, 누락된 정보가 있으면 보완을 요청합니다. 

### 책임과 권한
- 할당된 Issue와 PR에 대응합니다. 
- 기여한 코드의 active owner로서 다음에 대한 책임을 갖습니다.
  - 버그나 이슈를 해결합니다. 
  - 테스트에 항상 통과될 수 있게 합니다.
- Contributor는 오픈된 PR에 대해  /lgtm를 할 수 있습니다. 
- Issue나 PR을 자신에게 할당될 수 있습니다. 
- Member는 Contributor를 /cd @username 하여 review를 요청할 수 있습니다. 


## Committer

Committer는 프로젝트에 기여된 코드를 Review하고 Approve 할 수 있습니다. Committer는 코드 품질과 정확성에 초점을 맞춰서 Review를 하고, Approval을 위해 다음과 같은 부분까지도 고려해야 합니다. 
- 양방향 호환성
- API 및 Flag Convention
- 민감한 성능 및 정확성 문제
- 시스템의 다른 부분과 상호작용 

Committer 목록은 OWNER 파일 내 Committer entry에 기록됩니다. 

참고 : 기여한 코드가 수락되려면 지정된 Contributor의 Review와 더불어 한 명 이상의 Committer의 Approval이 필요합니다. 

### 요구 사항
Committer가 되기 위한 요구 사항은 다음과 같습니다. 
- Contributor가 된 이후 3개월 이상 된 자
- 최소 5개의 실질적인 PR에 대한 메인 Reviewer
- 최소 30개 이상의 PR에 대한 Review 혹은 Merge
- 자원하거나 혹은 프로젝트 내 다른 Committer에 의해 추천될 수 있음
- Maintainer에 의해 지명
  - 다른 Committer의 반대가 없어야 함
  - PR을 통해 OWNER 파일 업데이트

### 책임과 권한
- 대규모 코드 기여를 수락하기 위해서는 Committer의 Review와 Approval이 필요합니다. 
- 올바른 기술적 판단을 내립니다.  
- 프로젝트 품질 관리를 책임지고 code reviews를 충실히 수행합니다.
  - 다른 기능과의 종속성, 양방향 호환성, API 및 flag 정의 등과 같은 전체적인 영향에 중점으로 검토합니다. 
- Member와 Contributor의 멘토 역할을 합니다. 
- 코드 기여 수락 요청에 대해 Approve 합니다. 

## Maintainer

Maintainer는 프로젝트에 대한 기술 지휘권을 갖습니다. 프로젝트의 건전성에 대한 올바른 판단과 책임을 보여 주어야 합니다. 기술 방향을 설정하고, 설계에 대한 결정을 내리거나 승인해야 합니다. 

Maintainer 목록은 OWNER 파일 내 owner entry에 기록됩니다.

### 요구 사항
Maintainer가 되기 위한 기본적인 요구 사항은 다음과 같습니다. 

- 프로젝트의 기술적 목표와 방향에 대한 깊은 이해
- 프로젝트의 기술 영역에 대한 깊은 이해
- 다음을 모두 수행하여 설계 및 방향에 대한 지속적인 기여
  - 제안서 작성 및 검토
  - 토론 (이메일, GitHub issue, 미팅)을 시작, 참여하고 해결
  - PR을 설계하고 구현하는 데 있어서 미묘하고 복잡한 이슈 식별
- 구현 혹은 Review를 통해 프로젝트에 직접 기여

Maintainer가 되기 위한 세부 과정은 Project의 헌장에 정의되어야 합니다. 

### 책임과 권한
- 프로젝트에 대한 기술 설계 결정을 내리고 승인합니다. 
- 프로젝트의 기술적 방향과 우선순위를 설정합니다. 
- Milestone과 Release를 정의합니다. 
- 프로젝트 내 Committer, Contributor, Member의 멘토가 되어 가이드합니다. 
- 프로젝트의 지속적인 건전성을 보장합니다. 
- 안정적인 Release를 위한 적절한 테스트 coverage를 지정합니다.
- 토론 및 의사결정이 건전한 프로세스에 의해 수행되도록 합니다. 
- 다른 프로젝트의 Maintainer와 협력하여 전체적으로 프로젝트의 전반적인 건전성과 성공을 유지합니다. 