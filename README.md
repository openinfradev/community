# Hanurim Community Guide 

Hanurim Community에 오신 것을 환영합니다! 

- [Hanurim Community Guide](#hanurim-community-guide)
  - [Hanurim (HAm kke NU RIM; 함께 누림)](#hanurim-ham-kke-nu-rim-함께-누림)
    - [Supporting Companies & Organizations](#supporting-companies-and-organizations)
  - [프로젝트 소개](#프로젝트-소개)
    - [TACOPLAY](#tacoplay)
    - [DECAPOD (DEClarative APplication Orchestration & Delivery)](#decapod-declarative-application-orchestration--delivery)
    - [Shared Repositores](#shared-repositories)
  - [Governance](#governance)
  - [How to Use](#how-to-use)
  - [How to Develop](#how-to-develop)
  - [How to Contribute](#how-to-contribute)
  - [Communication](#communication)
  - [License](#license)
  - [Support](#support)


## Hanurim (HAm kke NU rim; 함께 누림) 
Hanurim 커뮤니티는 Open Infrastructure 및 Cloud Native Computing과 관련된 다양한 기술들을 오픈소스SW로 개발하고, 이와 관련된 커뮤니티를 구성하고 활성화 하기 위한 공간입니다.

### Supporting Companies & Organizations 
Hanurim 커뮤니티를 후원해주고 계시는 회사 (조직)은 다음과 같습니다. 
* SK Telecom (SK텔레콤)
* Cast.era 
* SM Solutions (에스엠솔루션즈)
* Bespin Global (베스핀 글로벌)
* XSLAB (엑세스랩)
* SK Broadband (SK브로드밴드)


## 프로젝트 소개

Hanurim에는 여러 개의 오픈소스SW 프로젝트들이 있습니다. Hanurim의 프로젝트들은 각각 고유의 기능/구조적 특징을 가지면서, 필요 시 서로 연계할 수 있도록 되어 있습니다.

Hanurim의 프로젝트는 두 개로 나뉘어 집니다. 첫번째로 Incubation Project로 시작이 되며, 그 이후 충분한 기능적 완성도와 안성정을 갖추게 되면 Stable Project로 전환 될 수 있습니다.

Incubation Project는 누구든지 생성을 제안할 수 있으며, Technical Committee에서 결정합니다.

### TACOPLAY

Ansible기반의 Baremetal, Container Runtime (Docker), Kubernetes를 설치하고 관리할 수 있는 playbook들을 제공합니다. 

최초 Kubernetes Cluster를 설치한 후에, 1) Containerized한 Ceph과 OpenStack, 그리고 LMA (Logging, Monitoring, Alerting) 툴들을 설치하여 Private Cloud를 구성할 수 있는 playbook들을 제공하며, 2) Kubernetes를 단독으로 사용하는 경우에는 decapod를 이용하여 Kubernetes LMA (Logging, Monitoring, Alerting), Service Mesh등 필요한 application들을 group으로 설치 가능하도록 제공합니다. 

  * https://github.com/openinfradev/tacoplay


### DECAPOD (DEClarative APplication Orchestration & Delivery)

Kustomize 기반의 YAML Document 구조화 기능을 제공하며, Helm, Argo Workflow, Argo CD등을 기반으로 연관된 Application들을 Grouping하고 Gitops 기반으로 선언적 배포 및 관리를 할 수 있는 기능을 제공합니다.

* [decapod-flow](https://github.com/openinfradev/decapod-flow) - Argo WorkflowTemplate들의 저장소
* [decapod-base-yaml](https://github.com/openinfradev/decapod-base-yaml) - Kustomize의 base가 되는 base resource yaml
* [decapod-site](https://github.com/openinfradev/decapod-site) - 환경에 맞게 kustomize를 통해 override할 수 있는 site yaml
* [decapod-manifests](https://github.com/openinfradev/decapod-manifests) - base와 site를 합쳐 렌더링한 결과의 저장소
* [kustomize-helm-transformer](https://github.com/openinfradev/kustomize-helm-transformer) - kustomize plugin to transform values in HelmRelease CR

### Shared Repositories  

Hanurim 에는 tacoplay나 decapod와 직접적으로 연관된 repository들 외에도 공통적으로 사용하는 helm chart, helm chart repo, ci/cd pipeline에서 사용되는 공통 library를 위한 repository들이 있습니다.


## Governance

Hanurim Community는 오픈소스의 협업과 공유 정신에 따라 누구든지 참여할 수 있으며, 모든 의사결정은 투명하게 공개됩니다. 이러한 원칙을 지속하기 위해 Membership과 Group에 대한 Governance 체계를 구축하였으며, Hanurim에 속한 모든 프로젝트는 이러한 Governance 체계에 따라 운영됩니다. 자세한 내용은 [Governance](governance/README.md)를 살펴보세요.

## How to Use

Hanurim Community 내 Project는 각각의 README에서 사용/설치/운영 방법을 자세히 소개합니다. 

> `need-to-improve` 
> * DECAPOD : 
> * ... :
> * ... :

## How to Develop

Hanurim Commnity 내 Project를 개발하기 위해 숙지해야할 사항이 있습니다. [빌드 가이드](developing/build.md), [테스트 가이드](develop/test.md), 코드 컨벤션, [CI/CD](developing/README.md), 릴리즈에 대한 상세한 내용은 [이곳](developing/README.md)을 참고하세요.

## How to Contribute

Hanurim Community는 모든 소스 코드와 문서를 완전히 공개하고 커뮤니티 구성원이 협업하여 개발하는 오픈소스 개발 방식을 따릅니다. 여러분의 소중한 기여로 Hanurim Community의 Project는 성장할 수 있습니다. 

여기서는 Hanurim Project에 기여하기 위한 방법을 자세히 설명합니다. : [Contributing](contributing/README.md)


## Communication 

Hanurim Community는 Project별로 Mailing List와 Slack 채널을 통해 소통하고 있습니다. 

각 Project의 Mailing List 및 Slack 채널 정보는 다음 페이지에서 확인하세요. : [Communication](communication/README.md)


## License

Hanurim Community는 모든 Project는 다음 라이선스에 따라 배포합니다. 
* 소스 코드 : [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)
* 소스 코드 이 외의 콘텐츠 (문서, 이미지 등) : [CC-BY-4.0](https://spdx.org/licenses/CC-BY-4.0.html)


## Support

Hanurim Community 운영과 관련한 문의/요청이 있을 경우 [Issue](https://github.com/openinfradev/community/issues/new)를 생성해서 의견 남겨 주세요.  

