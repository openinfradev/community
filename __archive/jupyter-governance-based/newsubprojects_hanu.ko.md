# 새로운 서브 프로젝트 프로세스

Project HANU는 HANU 거버넌스, 라이센스 및 기여 모델을 따르는 개발 팀이있는 GitHub 저장소 인 하위 프로젝트 세트로 구성됩니다. 공식적으로 지원 및 유지 관리되는 하위 프로젝트는 다음 GitHub 조직에서 호스팅됩니다.

* [github.com/hanu](https://github.com/hanu)
* [github.com/hanuhub](https://github.com/hanuhub)
* [github.com/hanulab](https://github.com/hanulab)
* [github.com/hanu-resources](https://github.com/hanu-resources)
* [github.com/hanu-widgets](https://github.com/hanu-widgets)
* [github.com/ipython](https://github.com/ipython)

이 문서는 새로운 하위 프로젝트가 다른 위치에서 이들 조직으로 생성되거나이 조직으로 이동되는 프로세스를 설명합니다. 새로운 서브 프로젝트를 생성하는 방법은 두 가지가 있습니다 :

1. [직접 서브 프로젝트 생성]
 * 예를 들어, 기존 서브 프로젝트에 기고자가 관련이 있지만 분리 가능한 코드를위한 새로운 Git 리포지토리를 생성하기로 결정한 경우
2. [기존 외부 서브 프로젝트의 통합]
 * 예를 들어, github.com/hanu-incubator의 프로젝트에 참여한 사람이 공식 HANU 조직 중 하나로 통합 제안서를 제출하고 운영위원회의 승인을받는 경우
 * 예를 들어, 제 3 자 프로젝트에 참여한 사람이 통합 제안서를 제출하고 운영위원회의 승인을받는 경우

github.com/hanu-incubator의 프로젝트는 아래의 기준을 충족하고이 문서의 뒷부분에 설명 된 통합 프로세스를 거치기 전까지 공식적으로 지원되고 유지 관리되는 하위 프로젝트로 간주되지 않습니다.

공식 하위 프로젝트의 기준

하위 프로젝트를 평가하여 공식 HANU 조직 중 하나에 통합하는 데 다음 기준이 사용됩니다. 서브 프로젝트를 개발하는 사람에 관계없이 서브 프로젝트에 적용됩니다. 하위 프로젝트는 다음을 수행해야합니다.

* 향후 개발을위한 지속 가능한 모델을 제공하는 적극적인 개발자 커뮤니티를 보유하십시오.
* 활발한 사용자 커뮤니티가 있습니다.
* 적절한 기술로 호스팅 된 문서 및 테스트와 함께 견고한 소프트웨어 엔지니어링을 사용하십시오 (문서 및 Travis 읽기는 사용할 수있는 기술의 예입니다).
* 지속적인 성장과 발전을 보여줍니다.
* 다른 공식 하위 프로젝트와 잘 통합하십시오.
* 여기에 설명 된 HANU 거버넌스 및 기여 모델에 따라 개발하십시오.
* 범위가 잘 정의되어 있어야합니다.
* pip, conda, npm, bower, docker 등과 같은 적절한 기술을 사용하여 포장하십시오.
* 일반적인 지침으로, 우리는 프로젝트에 경쟁하는 서브 프로젝트를 통합하는 것보다 기존 서브 프로젝트의 개선을 지원합니다.

하위 프로젝트를 공식 하위 프로젝트로 평가할 때 가장 중요한 질문은 다음과 같습니다. 커뮤니티와 운영위원회에서 하위 프로젝트를 공식적으로 개발하고 유지하기로 합의 하는가?

공식적인 서브 프로젝트 생성을위한 두 가지 경로가 이제 상세합니다.


## 다이렉트 서브 프로젝트 생성



## 기존 외부 하위 프로젝트의 통합

다른 경우, 통합을 위해 제안 된 서브 프로젝트는 공식 HANU 조직 외부에서 한동안 오픈 소스 소프트웨어로 존재하고 개발되었을 것입니다. 이 섹션에서는 이러한 기존 외부 하위 프로젝트의 통합 프로세스에 대해 설명합니다. 이 프로세스는 hanu-incubator GitHub 조직 (아래 참조)에서 인큐베이션 된 하위 프로젝트, 다른 GitHub 조직에서 개발 된 하위 프로젝트 또는 다른 공공 장소에서 오픈 소스 소프트웨어로 개발 된 하위 프로젝트에 적용됩니다.



### 법인 설립

기존의 외부 서브 프로젝트를 주요 HANU 조직 중 하나에 통합하려면 다음 제안 프로세스가 사용됩니다.

1. 서브 프로젝트 팀은 HANU / enhancement-proposals 저장소에 대해 주요 HANU 조직 중 하나에 서브 프로젝트를 포함시키기위한 개선 제안과 함께 풀 요청을 제출해야합니다. 개선 제안은 하위 프로젝트가 위의 각 기준을 어떻게 충족시키는 지 설명해야합니다.
2. 통합 제안은 해당 풀 요청을 사용하여 커뮤니티에서 논의됩니다.
3. 운영 협의회 (SC)의 합의에 의해 추천이 이루어집니다.

**타임 라인 :** SC는 신속하게 결정을 내릴 수 있도록 모든 노력을 기울여야합니다. 제안서에 대한 활발한 토론과 의견이 있다면 계속 진행해야하며 목소리가 들립니다. 그러나 모든 사람이 투표하기를 기다리는 불필요한 지연을 피하려면 다음 지침을 사용해야합니다.

* 제안에 따라 잠재적 이의 제기를 위해 일주일을 허용하십시오 (물론 명시 적 동의는 물론). 이의가 없으면 침묵을 동의로 취급하십시오.

* 한 달이 지났는데도 계속해서 활발한 의견 차이가있을 경우 프로젝트가 졸업 준비가되지 않았다는 강력한 신호로 취급되어야합니다 (필요한 경우 BDFL 선언은 여전히 ​​수락 요청을하는 데 사용될 수 있습니다).

운영위원회의 가능한 권장 사항은 다음과 같습니다.

* 기존 공식 Suproject에 통합.
* 새로운 공식 하위 프로젝트로 통합.
* 향후 내부 통합을 준비하기 위해 팀이 취할 수있는 단계에 대한 권장 사항과 함께 추가 내부 또는 외부 인큐베이션 (아래 참조).


### 법인

기존 외부 서브 프로젝트가 새로운 공식 서브 프로젝트로 통합되면 다음 단계가 수행됩니다.

1. 저장소는 HANU GitHub 주요 조직 중 하나로 이전됩니다.
2. 하위 프로젝트 팀에 하위 프로젝트 저장소에 대한 읽기 / 쓰기 권한이있는 하위 프로젝트에 대한 GitHub 팀이 생성됩니다.
3. 팀은 새로운 하위 프로젝트에 대한 공지와 함께 주피터 목록으로 이메일을 보냅니다.
4.이 통제 저장소에서 유지 보수되는 표준 Project HANU LICENSE 파일이 저장소에 추가됩니다.
5. 개별 파일의 저작권 고지는 Project HANU 라이센스에 설명 된 표준 형식으로 업데이트해야합니다.


## 서브 프로젝트의 인큐베이션

인큐베이션은 초기 HANU 공식 조직 외부에서 개발중인 하위 프로젝트 프로세스를 말합니다. 인큐베이션은 다음과 같은 특성을 가진 새로운 하위 프로젝트에 권장됩니다.

* 탐구가 필요한 중요한 답이없는 기술적 질문 또는 불확실성.
* 커뮤니티와 관련이없는 완전히 새로운 방향, 범위 또는 아이디어.
서브 프로젝트가 나머지 HANU와 어떻게 통합되는지 명확하지 않은 중요한 기존 코드 기반.
인큐베이션은 또한 더 넓은 커뮤니티가 주요 GitHub 조직의 안정적이고 공식적으로 지원 및 유지 관리되는 서브 프로젝트와 향후 포함을 위해 새롭게 개발되고있는 새로운 노력을 쉽게 구분할 수 있도록합니다.

부화가 특정 하위 프로젝트에 적합한 지에 대한 질문이있는 경우 관심있는 당사자는 주피터 목록에 대한 토론을 시작하여 커뮤니티 및 운영위원회 의견을 수렴해야합니다.



### [hanu-incubator] (https://github.com/hanu-incubator) 조직에서의 인큐베이션


주피터 인큐베이터 조직에서 인큐베이션의 목표는 다음과 같습니다.

기고자는 개인 및 조직의 기고 제한을 준수하면서 코드를 HANU 커뮤니티에 빠르고 쉽게 노출시킬 수 있습니다.
* 기고자는 커뮤니티 및 운영위원회와 협력하여 피드백을 조기에 수집하여 명확하고 간결한 통합 제안을 개발하고 개선하는 데 도움이 될 수 있습니다.
* 커뮤니티가 공식적으로 지원되는 서브 프로젝트와 커뮤니티 회원이 추구하는 실험적인 서브 프로젝트를 구별 할 수 있도록합니다.


인큐베이터 프로젝트를위한 리포지토리 관리 정책

프로젝트는 때때로 다양한 아이디어를 탐구하기 위해 새로운 저장소를 생성하기를 원할 수 있습니다. 이에 대한 기본 정책은 다음과 같습니다.

* 프로젝트 이름이 foo 인 경우 추가 인증을 요구하지 않고 foo-X라는 이름의 새 리포지토리를 만들 수 있습니다. 이 프로젝트는 더 넓은 HANU 채널에 대한 레포를 발표할지 여부가 충분한 관심이 있다고 생각하는지 여부를 결정할 수 있습니다 (분명히 이러한 레포지토리는 모두 공개되어 참여할 수 있습니다).

* 프로젝트가 bar라는 이름의 repo (다른 사람이 관심을 가질 수있는 최상위 이름)를 만들려면 주피터 목록에 게시해야합니다. 이 제안은 누군가가 심각한 이의를 제기하지 않는 한 이러한 요청은 가능한 한 신속하게 승인 될 것이라는 가정하에 논의 될 것입니다.

인큐베이션을위한 제안

하위 프로젝트 팀은 인큐베이션 제안서를 제출하여 주피터 인큐베이터 인큐베이션 프로세스를 시작할 수 있습니다. 이 프로세스는 가볍고 빠르게 설계되었습니다.

1. 제안자는 주피터 인큐베이터 / 제안서에 풀 요청을 제출하여 인큐베이션 신청서를 작성해야합니다.
2. 제안자는 주피터 메일 링리스트에 게시하여 커뮤니티에 자신의 의도를 발표해야합니다.
3. 제안 된 하위 프로젝트에는 운영 운영 협의회 회원 인 옹호자가 있어야합니다. 지지자의 역할은 하위 프로젝트 팀을 HANU 커뮤니티에 소개하고 인큐베이션 프로세스를 통해 그들을 돕는 것입니다. 옹호자가 서브 프로젝트의 실제 개발 및 설계에 관여 할 수 있지만 반드시 그럴 필요는 없습니다.
4. 부화 제안은 지역 사회가 논의하고 운영위원회의 합의에 의해 승인 또는 거부 될 것이다.
5. 승인되면 제안서 풀 요청이 병합되고 거부되면 요청이 마감됩니다.

### 인큐베이션 기간

주피터 인큐베이터 조직에서 하위 프로젝트의 인큐베이션이 승인되면 다음 단계가 수행됩니다.

1. GitHub 리포지토리는 hanu-incubator 조직에 생성됩니다
2. GitHub 팀은 Advocate를 포함하여 리포지토리에 대한 읽기 / 쓰기 액세스 권한으로 생성됩니다.
3.이 통제 저장소에서 유지 보수되는 표준 HANU LICENSE 파일이 새 저장소에 추가됩니다.
4. 운영 협의회 회원이 새로 Jucubter 목록에 부화 한 하위 프로젝트를 발표 할 것입니다.

잠복기의 목표는 서브 프로젝트가 활발한 개발자 및 사용자 커뮤니티를 개발할 것임을 입증하는 것입니다. 인큐베이션에 필요한 특정 시간은 없지만 대부분의 하위 프로젝트는 최소 6 개월에서 1 년 동안 인큐베이션 될 것으로 예상됩니다.


## 외부 인큐베이션

주피터 인큐베이터 조직 외부에서 인큐베이션도 가능합니다. 이 경우 공식적인 프로세스는 없습니다. 모든 개인 또는 조직은 자신의 개인 GitHub (또는 다른 VCS) 저장소에서 새 프로젝트를 작성하고 자신이 원하는대로 개발할 수 있습니다. 외부에서 생성되고 인큐베이션 된 하위 프로젝트가 공식 HANU 조직의 일부가 되려면이 문서의 맨 위에 나열된 기준을 충족해야하며 동일한 통합 프로세스를 따라야합니다.