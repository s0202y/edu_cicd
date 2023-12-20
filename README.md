# ktds-edu-cloud-cicd
클라우드 AP 소스코드 형상관리 전략 및 CI/CD 실전





# Cloud AP 소스코드 형상관리 전략 및 CI/CD 실전





# 1. 시작하기전에 ( [문서 보기](./beforebegin/beforebegin.md) )





# 2. 12 Factor 방법론 ( [문서 보기](./cloud-branch/12Factors.md) )

- 12 Factor 방법론이란?
- 왜 12 Factor 방법론을 사용해야 하나?
- 12 Factor 상세



# 3. Git Flow Branch 전략 ( [문서 보기](./cloud-branch/gitflow-branch.md) )

- Git Flow 개요
- git 명령들
- Git Flow Branch 전략
- Git Flow 실습




# 4. CI/CD ( [문서 보기](./cicd/CICD.md) )

- CI/CD 개요
- CI/CD 의미
- CI/CD 왜 사용해야 하는가?





# 5. Jenkins를 이용한 CI 구성 및 실습 ( [문서 보기](./jenkins/jenkins.md) )
- Jenkins란?
- 사전준비
  - K8S Resource
  - Dockerfile
  - PipeLine Template
- Jenkins Helm 설치 & 설정 (Cloud)
- Jenkins CI 수행하기 (Cloud)
- 다양한 옵션 사용



# 6. ArgoCD를 이용한 CD 구성 및 실습 ( [문서 보기](./argocd/argocd.md) )
- ArgoCD란?
- 사전준비
  - GitOps
- ArgoCD Helm 설치 & 설정 (Cloud)
- ArgoCD 배포하기 (Cloud)
- 다양한 배포전략 





#  별첨1. EduCluster Solution Setup ( [문서 보기](./cluster-setup/cluster-setup.md) )

## 1) EduCluster Setup

- kubernetes Install (k3s)
- 기타 Tool Setup

## 2) GitLab Setup

- deployment and service
- ingress
- 권한부여

## 3) Helm

- helm chart 와 Architecture
- helm client download install
- bitnami repo 추가





#  별첨2. Nexus Repository Setup ( [문서 보기](./nexus/nexus.md) )

## 1) Nexus

- Nexus란?

  - 사설레포지토리가 필요한 이유

- Nexus 설치 & 설정

- Image Upload/Download 테스트

  
