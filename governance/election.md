# 선거 

> 참고 : https://github.com/kubernetes/community/tree/master/events/elections

운영위원회 멤버는 선거를 통해 선출합니다. 이를 위한 선거 방식은 다음과 같습니다. 

## 투표 자격
- 작년 한해 동안 프로젝트에 50개 이상 기여 (이슈 생성, PR 생성, Comment 등 Github 활동 , 참고 : [devstats developer activity counts dashboard](https://k8s.devstats.cncf.io/d/13/developer-activity-counts-by-repository-group?orgId=1&var-period_name=Last%20year&var-metric=contributions&var-repogroup_name=All).)
- 위의 기준을 충족하지는 못하지만, 예외 투표 신청 (예: [voting exception form](https://www.surveymonkey.com/r/k8s-sc-election-2019))을 제출하고, 과반수 찬성 시 투표 참여 가능

## 입후보 자격
- 추천 혹은 자원자
- 각각 다른 조직의 3명의 투표 자격자에 의해 승인 (투표 자격이 있는 후보자는 자체 승인 할 수 있음)

## 선거 과정
선거는 [IRV method](https://en.wikipedia.org/wiki/Instant-runoff_voting) (Instant-runoff voting : 즉시 결선 투표) 방법으로 [CIVS](http://civs.cs.cornell.edu/)에서 시간 제한 [Condorcet](https://en.wikipedia.org/wiki/Condorcet_method) 순위를 사용하여 실시되면, 최고 득표자가 오픈된 의석에 선출됩니다. 

## 최대 참여 제한
다양성을 장려하기 위해 운영위원회에는 한 회사에서 1/3 이상의 멤버가 참여할 수 없습니다. 

## 선거 주기
- 운영위원회 멤버는 2년 임기로 선출하며, 4회 연임(8년)이 가능합니다. 
- 선거 주기는 멤버의 연속성을 위해 매년 약 절반의 의석이 재선되도록 조정합니다. 

## 선거 일정 및 운영
운영위원회는 선거를 운영할 선거관리관을 선발해 선거 일정을 수립합니다. 대략적인 선거 일정은 다음과 같습니다. (선거 절차 : [election procedure](https://git.k8s.io/community/events/elections/README.md))

- 7월말
    - 선거관리관 선발
    - 투표권자 자격 기준 수립
    - 선거 준비
- 9월
    - 공천기간, 선거
- 10월
    - 선거 종료
    - 선거 결과 발표

## 선거 관리관 선발
운영위원회는 다음 기준에 따라 3명의 선거 관리관을 선정합니다.

- 투표 자격이 있어야 합니다.
- 두 명은 이전 선거 관리관 경험자 중 선발하고, 나머지 한 명은 미경험자로 선발합니다. 
- 각각 소속이 달라야 합니다. 같은 회사에서 2명 이상 선발할 수 없습니다. 

선거 관리관은 선거 절차에 따라 선거를 관리합니다. (2020년 선거 : https://github.com/kubernetes/community/tree/master/events/elections/2020)

## 공석
선출된 운원위원회 멤버가 사퇴할 경우, 이전 선거에서 다음으로 많은 표를 얻은 후보에게 의석이 제공됩니다. 이 과정은 의석이 채워질 때까지 계속됩니다. 

그래도 의석이 채워지지 않을 경우, 해당 직책에 대한 특별 선거를 가능한 빨리 개최합니다. 

특별선거에서 선출된 운영위원회 멤버는 남은 기간에 관계 없이 이전 멤버의 남은 임기를 수행합니다. 