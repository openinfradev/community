# Group

- [Group](#group)
  - [운영 위원회 (Steering Committee)](#운영-위원회-steering-committee)
    - [주요 역할](#주요-역할)
  - [SIG (Special Interest Group)](#sig-special-interest-group)
    - [위원장](#위원장)
    - [헌장 (Charter)](#헌장-charter)
    - [소통](#소통)
    - [Guideline](#guideline)
  - [Working Groups](#working-groups)
  - [User Groups](#user-groups)


## 운영 위원회 (Steering Committee)
### 주요 역할
- Project-level governance
- Project-level 정책 관리 (예: Code of Conduct)
- 최종 의사 결정
- 하위 조직 관리

운영 위원회의 멤버는 [선거](election.md)를 통해 결정합니다.

## SIG (Special Interest Group)

SIG는 특정 분야의 주제와 관련하여 공통 목적을 가진 여러 프로젝트나 조직의 구성원이 협업하기 위해 구성된 조직입니다.  
SIG는 수직적으로 특정 component, function에 집중하거나, 수평적으로 여러 영역에 걸쳐있는 영역을 다룰 수 있습니다. 

- Vertical: Network, Storage, Node, Scheduling
- Horizontal: Scalability, Architecture
- Project: Testing, Release, Docs, PM, Contributor Experience

### 위원장
SIG에는 적어도 1명 이상의 위원장이 있어야 합니다. SIG 위원장은 다른 SIG, 운영위원회와 의사 소통 및 조정을 담당하며 다음의 역할을 수행합니다. 
- 헌장을 작성하거나 개선합니다. 
- 작업의 우선순위를 결정하는 방식을 정의합니다. 
- 현재 Release에 대한 SIG 개선 사항을 식별, 추적 및 유지합니다. 
- SIG 정보 (예: https://github.com/kubernetes/community/blob/master/sigs.yaml)를 항상 최신으로 유지합니다. 
- 미팅을 주관하고, 결과를 공개합니다. 
- SIG로의 기여 방법을 CONTRIBUTING.md에 작성하여 공개합니다. 
- 업데이트 사항을 커뮤니티 미팅 시 보고합니다. (예: https://github.com/kubernetes/community/blob/master/events/community-meeting.md)
- 연간 활동 사항을 연간 리포트에 제출합니다. (예: https://github.com/kubernetes/community/blob/master/committee-steering/governance/annual-reports.md)

### 헌장 (Charter)

각 SIG에는 범위 (주제, 코드 저장소, 디렉토리), 책임, 권한 영역, 리더쉽 역할 / 결정방법 및 충돌 해결 방법을 정의한 헌장이 있어야 합니다. 

> * 참고) SIG Charter Guide : https://github.com/kubernetes/community/blob/master/committee-steering/governance/README.md

### 소통
SIG에서의 소통은 투명하고 공개적이어야 합다. 다른 구성원이 회의, 토론, 결정에 대한 모든 기록을 열람할 수 있어야 합니다. 

### Guideline
SIG의 활동을 표준화하고, 투명성을 극대화하기 위하여 SIG는 다음 사항을 따라야 합니다. 

- SIG charter process에 따라 헌장을 만듭니다. (예: https://git.k8s.io/community/committee-steering/governance/README.md)
- 3주마다 최소 30분 동안 정기적으로 미팅을 가집니다. 
- 회의는 녹화하고, Community YouTube playlist에 공개합니다. (예: https://www.youtube.com/channel/UCZ2bu0qutTOM0tHYa_jkIwg)
- 최소 1년에 한번 메일링리스트를 통해 활동을 보고합니다. 
- 개인 이메일 대신 공식 커뮤니케이션 [채널](../communication/README.md)을 사용합니다.

## Working Groups
Working Group은 여러 SIG에 걸친 주제에 대한 토론 / 작업을 용이하게 하기 위한 커뮤니티입니다. 

## User Groups
User Group은 SIG나 Working Group에 적합하지는 않지만, 사용자와 관련이 있는 주제를 다룹니다. (예: continuos delivery)


