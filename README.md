####  
# Project | ML & DL
<a href="https://drive.google.com/file/d/1yz26V0NXY0HELWS6SWk5FwKcWXonJ9Jc/view?usp=share_link"><img src="https://img.shields.io/badge/PPT-PUBG Finish Placement Prediction PT-2677d0"/></a> <a href="https://drive.google.com/file/d/1RJNDRCeWPNlgSgkD7kC_1u-9MozjumU2/view?usp=share_link"><img src="https://img.shields.io/badge/PPT-Nucleus Segmentation PT-2677d0"/></a>
####
### 1. ML | PUBG Finish Placement Prediction
#### 📌 [프로젝트 설명]
- 2022년 6월 7일~2022년 6월 21일(약 2주)
- 유저의 final stats를 예측하는 EDA(Exploratory Data Analysis) 위주의 ML 프로젝트
- 이어드림 스쿨 40개 조 중, 우수 프로젝트 선정 및 PT 진행
####
#### 📌 [주요 과정]
- 데이터 용량 감소 후 로드 / 데이터 기본 정보 확인 및 결측치 파악
- target, categorical, numerical 분류에 따라 총 28개의 feature 상세 분석
- correlation에 기반한 6개의 가설 설정 및 검증 결과 도출
- data cleaning 및 feature selection 진행
- 경우의 수에 따른 모델 생성 및 평가 진행
####
#### 📌 [기술 스택]
- <img src="https://img.shields.io/badge/Python-NumPy / pandas / matplotlib / seaborn / sklearn / statsmodels-4479A1"/>
- <img src="https://img.shields.io/badge/model-LinearRegression / Ridge / Lasso / ElasticNet / RandomForestRegressor / XGBRegressor-4479A1"/>
- <img src="https://img.shields.io/badge/data analysis-regression / correlation / multicollinearity-FF6600"/>
- <img src="https://img.shields.io/badge/data visualization-displot / scatterplot / lineplot / barplot / heatmap / msno.bar & matrix-FF6600"/>
##
### 2. DL | Nucleus Segmentation
####
#### 📌 [프로젝트 설명]
- 2022년 7월 21일~2022년 8월 5일(약 2주)
- 세포 이미지 내 핵(nucleus)을 식별하는 instance segmentation 위주의 DL 프로젝트 
- 이어드림 스쿨 21개 조 중, 우수 프로젝트 선정 및 PT 진행
####
#### 📌 [주요 과정]
- image와 mask의 경로를 추출하는 로직 함수화 및 시각화 진행
- cluster center에 기반한 clustering 진행
- image_id, image & mask 경로, cluster 정보가 포함된 dataframe 생성
- cluster에 따른 시각화 진행
- 단일 mask에 대한 외곽선 정보 추출 연습
- 전체 mask의 polygon과 bounding box 정보를 추출하는 로직 함수화
- 추출된 annotation 정보를 COCO format으로 변환하는 로직 함수화
- COCO API를 사용해 instance segmentation 시각화 진행
####
#### 📌 [기술 스택]
-
    <div align="left"><img src="https://img.shields.io/badge/Python-NumPy / pandas / matplotlib / sklearn / cv2-4479A1"/>
-
    <div align="left"><img src="https://img.shields.io/badge/computer vision-TensorFlow / OpenCV-FF6600"/>
    <img src="https://img.shields.io/badge/algorithm-K--means clustering-FF6600"/>
    <img src="https://img.shields.io/badge/API-pycocotools-FF6600"/><br>
####
#### 📌 [시각화 결과]
|<img src="https://user-images.githubusercontent.com/109773795/183776882-572ee620-287c-4867-8b63-01ac0c32370c.png" width="950" height="150"/><img src="https://user-images.githubusercontent.com/109773795/183776651-838bf36e-336c-4bb2-86e0-2031f8f1a663.png" width="950" height="150"/>|
|:---:|
####
