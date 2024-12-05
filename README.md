# 2024 스타랩 - 분산엣지를 위한 딥러닝 모델생성 플랫폼(2단계)

## 소개

경희대학교 홍충선 교수님 연구실에서 SW스타랩 데모 시연을 위한 웹 어플리케이션을 구현한 레포지토리입니다.

![소개](/video.mov)

## 웹 어플리케이션 주요 기능 및 내용

### 0. 사용자 인증

- 본 플랫폼은 운영자의 허가를 받은 사용자만 접근 가능함
- 사용자는 로그인을 통해 플랫폼에 접근할 수 있음
- 서버의 자원 문제로 임의의 회원가입은 지원하지 않음

![사용자인증](/00_authentication.png)

### 1. 플랫폼 소개

- 메인 페이지에서는 본 연구 및 어플리케이션의 전체적인 구성을 동영상으로 설명함
- 사용자는 메인 페이지에 도달하면 자동 재생된 동영상을 통해 서비스의 주요 기능을 파악할 수 있음
- 동영상이 종료되면 팝업 창이 나타나며, 사용자가 모델 생성 페이지로 접근 가능하도록 안내함

![플랫폼소개](/01_overview.png)

### 2. 데이터 분석

- 사용자는 데이터 분석을 위해 데이터를 업로드하고 딥러닝을 이용하고자 하는 테스크(목적)을 설정함
- 본 플랫폼에서는 사용자의 데이터 및 테스크에 맞게 최적의 데이터 분석 방법을 자동 적용하여 결과를 제공함

![데이터분석](/02_dataanalysis.png)

### 3. 모델 검색

- 사용자는 데이터 분석 결과를 바탕으로 생성된 모델을 검색할 수 있음
- 기본적으로는 본 플랫폼의 알고리즘에 의거해 가장 적합한 모델을 추천함
- 사용자는 추천된 모델을 선택하거나, 직접 다른 모델을 선택할 수 있음
- 추가로, 다양한 하이퍼파라미터를 설정하여 모델을 생성할 수 있음
- 모델 생성이 완료되면 사용자는 시각화된 모델 구조를 확인할 수 있음

![모델검색](/03_modelsearch.png)

### 4. 지식 증류

- 사용자는 모델 생성 결과를 바탕으로 지식 증류를 수행할 수 있음
- 기본적으로는 지식 증류를 적용하지 않으나, 사용자의 분산엣지 환경에 맞게 지식 증류를 적용할 수 있음
- 지식 증류가 완료되면 사용자는 시각화된 모델 구조를 확인할 수 있음

![지식증류](/04_knowledgedistillation.png)

### 5. 데이터 전처리

- 사용자의 데이터 전처리를 위해 기존에 업로드한 데이터를 기반으로 전처리 방식을 추천함
- 추천된 전처리 방식을 적용하거나, 사용자가 직접 전처리 방식을 설정할 수 있음
- 선택된 전처리 전/후 데이터를 시각화하여 사용자가 전처리 결과를 확인할 수 있음

![데이터전처리](/05_preprocessing.png)

### 6. 모델 학습

- 사용자는 전처리된 데이터와 생성된 모델을 바탕으로 모델 학습을 수행할 수 있음
- 학습 과정은 각종 그래프와 지표를 통해 시각화되어 제공됨

![모델학습](/06_training.png)

### 7. 학습 결과 및 모델 평가

- 사용자는 학습 결과 및 모델 평가를 위한 그래프 및 지표를 확인할 수 있음
- 사용자는 결과를 바탕으로 생성된 모델이 적합한지 판단하여 모델을 다운로드할 수 있음

![결과](/07_result.png)
