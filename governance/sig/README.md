# HANU SIG (Special Interest Group)

- [HANU SIG (Special Interest Group)](#hanu-sig-special-interest-group)
  - [HANU SIG](#hanu-sig)
  - [생성 절차](#생성-절차)
  - [가이드라인](#가이드라인)
  - [리더](#리더)

HANU의 SIG는 프로젝트 외에 Cloud Native Infrastructure와 관련하여 특정 주제에 대한 테스트, 논의, 스터디 등을 수행하기 위한 그룹입니다. 

## HANU SIG

현재 HANU에는 다음의 SIG가 활동하고 있습니다. 

- [ARM SIG](sig-arm/README.md) : ARM 서버에 Kubernetes 적용 등 Cloud Infra 구축에 필요한 서버들을 새롭게 정의하기 위한 SIG 입니다. 

## 생성 절차

HANU의 멤버라면 누구나 SIG 결성을 제안할 수 있으며, Technical Committee가 승인 여부를 결정합니다. SIG 생성 절차는 다음과 같습니다. 

1. 신규 SIG 생성 제안자(리더)는 다음 두개 파일을 생성/변경합니다. 
   1. 헌장 파일
       - SIG에는 범위(주제, 코드 저장소, 디렉토리), 책임, 권한 영역, 리더쉽 역할 / 결정방법 및 충돌 해결 방법을 정의한 헌장이 있어야 합니다. 
       - [SIG 헌장 template 파일](sig-charter-template.md)을 Copy하여 community/governance/sig/sig-YOURSIG/charter.md을 만듭니다. 
       - 생성한 Your SIG용 헌장(charter.md)의 내용을 채웁니다. (예: [charter-sig-arm.md](sig-arm/charter-sig-arm.md))
   2. sigs.yaml 파일
       - sigs.yaml 파일에 신규 SIG의 내용을 적용하여 업데이트합니다. 
2. 생성/변경한 두개의 파일로 Pull Request를 생성하여 Technical Comittee에 Review를 요청합니다. 
   - 이때 Title은 "SIG Charter Proposal: YOURSIG"로 지정합니다. 일반적으로 일주일 이내에 피드백을 받을 수 있습니다. 
3. 승인되면, Technical Comittee는 PR을 merge합니다. 
4. SIG 생성이 완료되었습니다. 다음 가이드라인에 따라 SIG 활동을 수행합니다. 

## 가이드라인
SIG의 활동을 표준화하고, 투명성을 극대화하기 위하여 HANU의 SIG는 다음 사항을 따라야 합니다. 
- SIG에서의 소통은 투명하고 공개적이어야 합다. 다른 구성원이 회의, 토론, 결정에 대한 모든 기록을 열람할 수 있어야 합니다. 
  - 커뮤니케이션은 개인 이메일 대신 공식 커뮤니케이션 [채널](../communication/README.md)을 사용합니다.
- 3주마다 최소 30분 동안 정기적으로 미팅을 가집니다. 
- 회의는 녹화하고, Community YouTube playlist에 공개합니다. (예: https://www.youtube.com/channel/UCZ2bu0qutTOM0tHYa_jkIwg)
- 최소 1년에 한번 메일링리스트를 통해 활동을 보고합니다. 

## 리더
SIG에는 적어도 1명 이상의 리더가 있어야 합니다. SIG 리더는 다른 SIG, 기술 위원회와 의사 소통 및 조정을 담당하며 다음의 역할을 수행합니다. 
- 헌장을 작성하거나 개선합니다. 
- 작업의 우선순위를 결정하는 방식을 정의합니다. 
- 현재 Release에 대한 SIG 개선 사항을 식별, 추적 및 유지합니다. 
- SIG 정보 (예: https://github.com/kubernetes/community/blob/master/sigs.yaml)를 항상 최신으로 유지합니다. 
- 미팅을 주관하고, 결과를 공개합니다. 
- SIG로의 기여 방법을 CONTRIBUTING.md에 작성하여 공개합니다. 
- 업데이트 사항을 커뮤니티 미팅 시 보고합니다. (예: https://github.com/kubernetes/community/blob/master/events/community-meeting.md)
- 연간 활동 사항을 연간 리포트에 제출합니다. (예: https://github.com/kubernetes/community/blob/master/committee-steering/governance/annual-reports.md)

