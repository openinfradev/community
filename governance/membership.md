# Membership
- [Membership](#membership)
  - [Member](#member)
    - [요구사항](#요구사항)
    - [책임과 권한](#책임과-권한)
  - [Reviewer](#reviewer)
    - [요구 사항](#요구-사항)
    - [책임과 권한](#책임과-권한-1)
  - [Appoval](#appoval)
    - [요구 사항](#요구-사항-1)
    - [책임과 권한](#책임과-권한-2)
  - [Project Owner](#project-owner)
    - [요구 사항](#요구-사항-2)
    - [책임과 권한](#책임과-권한-3)


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

Member는 GitHub organization의 Member로 등록됩니다. 

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

### 책임과 권한

- 할당된 Issue와 PR에 대응합니다. 
- 그들이 기여한 코드의 active owner입니다.
  - 코드는 잘 테스트되어야 합니다.
  - 테스트는 항상 통과되어야 합니다.
  - 버그나 이슈를 해결합니다. 
- 멤버는 오픈된 PR에 대해  /lgtm를 할 수 있습니다. 
- Issue나 PR에 대해 할당될 수 있으며, 사람들은 멤버에게 /cd @username 하여 review 요청할 수 있습니다. 


## Reviewer

Reviewer는 프로젝트 내의 코드 품질과 정확성을 review할 수 있습니다. Reviewer는 코드베이스와 소프트웨어 엔지니어링 원칙에 대해 잘 알고 있어야 합니다. 

Reviewer 목록은 OWNER 파일 내 reviewer entry에 기록됩니다. 

참고 : 기여한 코드가 수락되려면 지정된 Reviewer와 더불어 한 명 이상의 Approval의 승인이 필요합니다. 

### 요구 사항
Reviewer가 되기 위한 요구 사항은 다음과 같습니다. 

- Member가 된 이후 3개월 이상 된 자
- 최소 5개의 PR에 대한 메인 Reviewer
- 최소 20개 이상의 실질적인 PR을 코드베이스에 Merge
- 코드베이스를 잘 알고 있음
- Project Owner가 후원
  - 다른 Approver의 반대가 없어야 함
  - PR을 통해 OWNER 파일 업데이트
- 자원하거나 혹은 프로젝트 내 다른 Approver에 의해 지명될 수 있음

### 책임과 권한
- 대규모 코드 기여를 수락하기 위해서는 Reviewer의 검토가 필요합니다. 
- 프로젝트 품질 관리를 책임지고 code reviews를 충실히 수행합니다.
- 프로젝트와 관련된 PR의 review가 할당됩니다.
- 프로젝트와 관련된 bug가 할당됩니다.

## Appoval

Approver는 코드 기여를 review하고 approve할 수 있습니다. Review는 코드 품질과 정확성에 초점을 맞추고 있지만, Approal은 다음과 같은 부분까지도 고려하여 전체적인 관점의 검토에 중점을 둡니다. 

- 양방향 호환성
- API 및 플래그 convention
- 민감한 성능 및 정확성 문제
- 시스템의 다른 부분과 상호작용 

Approver 목록은 OWNER 파일 내 approver entry에 기록됩니다. 

### 요구 사항
Approver가 되기 위한 요구 사항은 다음과 같습니다. 

- Reviewer가 된 이후 3개월 이상 된 자
- 최소 5개의 실질적인 PR에 대한 메인 Reviewer
- 최소 30개 이상의 PR에 대한 Review 혹은 Merge
- Project Owner에 의해 지명
  - 다른 Project Owner의 반대가 없어야 함
  - PR을 통해 OWNER 파일 업데이트

### 책임과 권한
- 대규모 코드 기여를 수락하기 위해서는 Approver의 수락이 필요합니다. 
- 올바른 기술적 판단을 내립니다.  
- 프로젝트 품질 관리를 책임지고 code reviews를 충실히 수행합니다.
  - 다른 기능과의 종속성, 양방향 호환성, API 및 flag 정의 등과 같은 전체적인 영향에 중점으로 검토합니다. 
- Member와 Contributor의 멘토 역할을 합니다. 
- 코드 기여 수락 요청에 대해 Approve합니다. 


## Project Owner

Project Owner는 프로젝트에 대한 기술 지휘권을 갖습니다. 프로젝트의 건전성에 대한 올바른 판단과 책임을 보여 주어야 합니다. 기술 방향을 설정하고, 설계에 대한 결정을 내리거나 승인해야 합니다. 

Project Owner 목록은 OWNER 파일 내 owner entry에 기록되고, sigs.yaml subproject.owners에 정의됩니다.

### 요구 사항
Project Owner가 되기 위한 기본적인 요구 사항은 다음과 같습니다. 

- 프로젝트의 기술적 목표와 방향에 대한 깊은 이해
- 프로젝트의 기술 영역에 대한 깊은 이해
- 다음을 모두 수행하여 설계 및 방향에 대한 지속적인 기여
  - 제안서 작성 및 검토
  - 토론 (이메일, GitHub issue, 미팅)을 시작, 참여하고 해결
  - PR을 설계하고 구현하는데 있어서 미묘하고 복잡한 이슈 식별
- 구현 혹은 Review를 통해 프로젝트에 직접 기여

Project Owner가 되기 위한 세부 과정은 Project를 소유한 SIG의 헌장에 정의되어야 합니다. 

### 책임과 권한
- 프로젝트에 대한 기술 설계 결정을 내리고 승인합니다. 
- 프로젝트의 기술적 방향과 우선순위를 설정합니다. 
- Milestone과 Release를 정의합니다. 
- 프로젝트 내 Approver, Reviewer, Member의 멘토가 되어 가이드합니다. 
- 프로젝트의 지속적인 건정성을 보장합니다. 
  - 안정적인 Release를 위한 적절한 테스트 coverage를 지정합니다.
  - 테스트는 신뢰성있게 수행해야 하며, Fail시 수정되어야 합니다. 
- 토론 및 의사결정이 건전한 프로세스에 의해 수행되도록 합니다. 
- 다른 프로젝트의 Project Owner와 협력하여 전체적으로 프로젝트의 전반적인 건전성과 성공을 유지합니다. 