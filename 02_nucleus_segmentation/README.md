####
## Objectives
- 가이드 강의를 참고해 스스로 코드를 작성하며 Instance Segmentation에 대한 심도있는 학습 진행
- 기존 도메인 지식이 없는 주제를 선택해 데이터 내에서 유의미한 인사이트를 찾는 분석 경험 축적
- Kaggle 데이터를 핸들링하는 경험 축적


####
## Skills
-
    <div align="left"><img src="https://img.shields.io/badge/[Python]-NumPy / pandas / matplotlib / sklearn / cv2-4479A1"/>
    <img src="https://img.shields.io/badge/[Computer vision]-TensorFlow / OpenCV-FF6600"/>

-
    <div align="left"><img src="https://img.shields.io/badge/[API]-pycocotools-428813"/>
    <img src="https://img.shields.io/badge/[Algorithm]-K--Means Clustering-428813"/><br> 
    
####
## Contents
- Download the Dataset - Kaggle API를 활용해 Dataset 다운로드
- Explore the Data - Image / Mask 경로 추출 로직 함수화 및 시각화 진행
- K-Means Clustering - Cluster Center에 기반한 Clustering 진행
- Create a Dataframe - image_id / Image & Mask 경로 / Cluster 정보 포함된 Dataframe 생성
- Visualize the Data - Cluster(Stainded & Bright-field & Fluorescence)에 따른 시각화 진행
- Find and Draw Contours - 단일 Mask에 대한 외곽선 정보 추출 연습
- Get Annotation Information - 전체 Mask의 Polygon & Bounding Box 정보 추출 로직 함수화
- Convert the Dataset to COCO Format - 추출된 Annotation 정보를 활용해 COCO Format 변환 로직 함수화
- Visualize the Data Using pycocotools - COCO API를 활용해 Instance Segementation 시각화 진행
<img src="https://user-images.githubusercontent.com/109773795/183776882-572ee620-287c-4867-8b63-01ac0c32370c.png" width="950" height="150"/>
<img src="https://user-images.githubusercontent.com/109773795/183776651-838bf36e-336c-4bb2-86e0-2031f8f1a663.png" width="950" height="150"/>

####
## Afterthoughts
- COCO Dataset 변환 과정을 통해 COCO Format의 Annotation 정보를 상세히 살펴볼 수 있었습니다.
- 추출된 Annotation 정보를 바탕으로 Instance Segmentation 진행 과정을 심도있게 실습할 수 있었습니다. 
####
## Reference
- [[Kaggle] 2018 Data Science Bowl - Nucleus Segmentation](https://www.kaggle.com/competitions/data-science-bowl-2018)
####
