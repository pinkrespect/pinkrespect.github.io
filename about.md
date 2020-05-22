---
layout: page
title: About
---

# 김 양선 Yangseon Kim
## Contact

- Miss.sonagi@gmail.com / 010-5764-5025
- github: http://github.com/pinkrespect
- acmicpc: https://www.acmicpc.net/user/didee

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
  * Flask(Python Web Framework)
  * Django(Python Web Framework)
  * Nginx(Web Server)
  * AWS(Amazon Web Service)

- ETC
  * GIT (Version Control System)

----------------------

## 경력 Carrier
역순 정렬되어 있습니다.

### 에스알유니버스
2020.03 - 재직중

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
    - 진행 중

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
   - 참고 논문: [grad-CAM](https://arxiv.org/abs/1610.02391)
     - 신경망(Neural Network)의 주목도(Attention)를 표현할 수 있고, 레이어 별로 주목하는 위치가 다르다는 것을 알 수 있었음
   - 사용 기술
     - Shell Script, Python3+pytorch+TensorboardX+Matplotlib

3. Meta-Learning
   - 이미지의 수를 적게 학습할 수 있는지에 관건을 둔 프로젝트
   - 그래프 이론(Graph Theory)에 기반을 두고 기존 코드 확인 및 트레이닝 & 인퍼런싱
------------------

## 교육 Education
- 전주 대학교 Jeonju Univ. - 공과대학 컴퓨터 공학과 학사 2015.03 – 2020.08(졸업 예정)

---------------------

## 경험 Experience

### 학과 동아리 활동
- DB LAB(담당 교수: 이인홍 교수)
   * 신입생 코딩 교육 주최 - 1년, C언어, 토이 프로젝트 개발
   * 실습실 컴퓨터 40대 관리 - 실습실 컴퓨터 관리 및 초기화, 필요 프로그램(Oracle DB) 설치
   * DB LAB 전용 Windows Server 관리 - 개인 폴더 관리 및 권한 설정, 백업 진행
   * DB LAB 소유 컴퓨터 관리 - 소유 신고, 정적 IP 배당

### 수업 활동
- 소프트웨어 기초 설계 – 공강 강의실 알리미
   * 사용 언어: C
   * 현재 수업이 없어 비어있는 공강 강의실을 알려주는 프로그램 제작
   * 직책: 팀장
   * PPT 제작 및 발표, 프로그램 UI 및 클래스 단위 노동 배분, 전체/ 부분 프로그램의 디버그 진행

- 생활 속의 빅 데이터 이해와 분석 – 워드 클라우드 제작
   * 사용 언어: R, Tableau
   * 전체 단어에서 사용 빈도수가 높은 순으로 워드 클라우드 제작

- 정보보호개론, 수치 해석 - FTP 서버 관리
   * 수업에 필요한 PPT 업로드
   * Windows 환경, Apache 이용

- 연세대학교 학점 교류(3학년 2학기, 중도 휴학)
   * 알고리즘, 시스템 프로그래밍, 프로그래밍 언어 수강

- 개인 프로젝트(종합 설계) - WEB과 연동되는 POS 시스템
   * 사용 언어: JAVA, Vue.js, WEB
   * 직책: 팀원
   * Vue.js 및 WEB 개발


### 외부 활동
- 페미위키 – 서버 관리
   * 로드 밸런싱 및 서버 이전(Lightsail -> EC2)


### 수상 경력 Awards
- 성적 우수(최우등)
   * 시상: 총장
   *  수상 일자: 2016.08.26

- 성적 우수(우등)
   * 시상: 학장
   * 수상 일자: 2016.02.26

- 성적 우수(우등)
   * 시상: 학장
   * 수상 일자: 2015.08.28
