---
layout: page
title: About
---

# 김 양선 Yangseon Kim
## Contact

- Miss.sonagi@gmail.com / 010-5764-5025
- github: http://github.com/pinkrespect
- acmicpc: https://www.acmicpc.net/user/didee
- ClubHouse: @Seon_k

## 자기 소개 Self introduction
### 진로 설정

- AI 연구원 > 백엔드 엔지니어 -> DEVOps

### 미션

- 가지고 있는 기술을 활용하여 성 소수자, 장애인, 청소년, 사회 취약 계층 및 기타 작은 인원을 위한 마이크로 서비스 지원

### 작은 목표들

- DB 설계에서 확장성 고려하여 최고의 디자인 해 보기
- 좋은 동료와 함께 협업하며 좋은 동료가 되는 방법에 대해서 고민하기
- 성 소수자 친구들을 대할 때, 그들이 직면한 어려움을 어떠한 서비스로 풀어낼 지 고민해 보기
- 혼자 일하는 개발자보다 같이 일하면 120%의 결과물을 낼 수 있는 팀원이 되기


### 강점과 약점
#### 강점
- 일 처리 속도가 빠름
- 작은 단위로 잘라내는 능력 있음
- 새로 나오는 개발자용 서비스를 빠르게 적용할 수 있음
- 의사 소통 능력 및 대인 관계 좋은 편
- 논문 빠르게 읽는 편

#### 약점
- 일 처리 속도가 빠르지만 마감이 무기한 또는 너무 긴 일에 대해서 준비가 약함
- 할 일을 다 해버리면 집에 빠르게 퇴근함
- 점심 시간에 밥을 안먹고 잠


-----------------

## 기술 Skills
### 언어

- Python3, JAVA, ECMAScript

### 환경

- Unix-like system(Arch Linux, Manjaro Linux, Ubuntu)
- macOs
- CMD(bash, zsh) + iterm2
- Pylint, ESLint, Vimplug, Zplug
- Vim(Text Editor)

### 기타

- Container Orchestration tool
  * Docker & Kubernetes

- WEB
  * Vue.js(JavaScript Framework)
  
- Backend stack
  * GraphQL - Strawberry, Graphene
  * RESTFul API
  * Flask(Python Web Framework)
  * Django(Python Web Framework)
  * Nginx, AWSGI, ASGI, GUnicorn
  * Uvicorn
  
- Cloud Service
  * AWS(Amazon Web Service)
  * GCP(Google Cloud Platform)
  * MS Azure

- Database
  * MYSql 5.7, 8.0
  * DBeaver, Sequel Pro
  * Postman (HTTP data transfer test)

- ETC
  * GIT (Version Control System)
  * GIT Actions
  * JIRA (Project Manage) & Kanban system

----------------------

## 경력 Carrier
역순 정렬되어 있습니다.

### (주)딥헬릭스
2020.09 - 2020-10

Backend Developer(연구원)

물리 서버 관리 및 클라우드 서버 관리를 담당합니다. 물리 서버의 경우 AI 프로젝트에 적합한 환경으로 구성하는데 Terraform을 사용합니다. WEB Backend 작업의 경우, Frontend에서 원하는 데이터를 RESTFul API를 통해 Json Data로 보냅니다.

#### 프로젝트
1. 딥헬릭스 에듀
    - 온라인 강의 플랫폼 사이트 제작 프로젝트
    - 사용 기술
        - Docker + Kubernetis, AWS, Python3 + Flask, MYSql, SQLAlchemy

2. 물리 서버 구성
    - 진행 중

### 에스알유니버스
2020.03 - 2020.07

딥러닝 연구원

2D Image를 활용한 컨텐츠 개발의 기초가 되는 기술을 연구했습니다. 2D 이미지를 조작(Manipulation)하거나, 있던 물체를 사라지게(Inpainting) 하는 기술 뿐만 아니라, 이미 찍혀 있는 사진의 테마를 다른 그림 또는 디자인으로 변경(Style Transfer)하는 연구를 했습니다.

#### 프로젝트
1. 스타일 전이 학습(Style Transfer Learning)
    - 2D Image, Video에 다른 이미지(주로 그림)의 스타일을 입히는 프로젝트
    - 참고 논문
        - [Style Transfer by Relaxed Optimal Transport and Self-Similarity](https://arxiv.org/pdf/1904.12785.pdf)
        - [ReCoNet: Real-time Coherent Video StyleTransfer Network](https://arxiv.org/pdf/1807.01197.pdf)
            - Video를 Frame 별로 잘라 각각 Style Transfer를 시키는 방식은, 배경이나 고정되어 있는 물체를 움직이는 것처럼 보이게 하기 때문에, ReCoNet의 방식이 더 효율적
    - 사용 기술
        - Shell Script, (사용자를 위한)Flask+Jinja2, Python3+pytorch+Tensorflow

2. 2D 이미지 조작, 수정(2D Image Inpainting)

### 딥인스펙션 인공지능 연구실
2019.11 - 2020.02

연구원

건축물의 2D Image에 대한 결함을 효율적으로 모델이 학습하고, 지역 추천(Regional Proposal)을 할 수 있도록 만들었습니다. 또한, 모델의 학습(Training)에 사용할 수 있는 사진이 제한적이므로, 그런 데이터를 수정
하고 변환해서 학습에 사용하여 효율적인 지역 추천을 할 수 있도록 했습니다.

#### 프로젝트
1. drl-RPN
    - 결함 지역 추천을 강화 학습(Reinforcement Learning)으로 할 수 있는지에 대한 프로젝트
    - 참고 논문: [Deep Reinforcement Learning of Region Proposal Network for Object Detection](http://openaccess.thecvf.com/content_cvpr_2018/papers/Pirinen_Deep_Reinforcement_Learning_CVPR_2018_paper.pdf)
      - 상황별 클래스 확률의 조정(Contextual Class Probability Adjustment)이 다른 Reinforcement Learning과의 차이점
    - 사용 기술
      - Shell Script, Python3+Pytorch

2. LSTM
    - [grad-CAM](https://arxiv.org/abs/1610.02391)에서 추출된 단어를 통한 문장 생성 프로젝트
    - 사용 기술
      - Python3+pytorch

3. grad-CAM
   - 결함 지역 추천을 gradient로 표현하여 출력하는 프로젝트
   - 참고 논문: [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391)
     - 신경망(Neural Network)의 주목도(Attention)를 표현할 수 있고, 레이어 별로 주목하는 위치가 다르다는 것을 알 수 있었음
   - 사용 기술
     - Shell Script, Python3+pytorch+TensorboardX+Matplotlib

3. Meta-Learning
   - 이미지의 수를 적게 학습할 수 있는지에 관건을 둔 프로젝트
   - 그래프 이론(Graph Theory)에 기반을 두고 기존 코드 확인 및 트레이닝 & 인퍼런싱
   
---------------------

## 경험 Experience

### 외부 활동
- 페미위키 – 서버 관리
   * 로드 밸런싱 및 서버 이전(Lightsail -> EC2)

- Python3 GraphQL Library ![*Strawberry*](https://strawberry.rocks/) Contributer
