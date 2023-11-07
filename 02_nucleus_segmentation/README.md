####
## 📌 Nucleus Segmentation 
#### ► [Objectives]
- 가이드 강의를 참고해 스스로 코드를 작성하며 instance segmentation에 대한 심도있는 학습 진행
- 기존 도메인 지식이 없는 주제를 선택해 데이터 내에서 유의미한 인사이트를 찾는 분석 경험 축적
- Kaggle 데이터를 핸들링하는 경험 축적
####
#### ► [Skills]
-
    <div align="left"><img src="https://img.shields.io/badge/[Python]-NumPy / pandas / matplotlib / sklearn / cv2-4479A1"/>

-
    <div align="left"><img src="https://img.shields.io/badge/[computer vision]-TensorFlow / OpenCV-FF6600"/>
    <img src="https://img.shields.io/badge/[algorithm]-K--means clustering-FF6600"/>
    <img src="https://img.shields.io/badge/[API]-pycocotools-FF6600"/><br> 
    
####
#### ► [Contents]
- download the dataset: Kaggle API를 활용해 dataset 다운로드
- explore the data: image와 mask의 경로를 추출하는 로직 함수화 및 시각화 진행
- K-means clustering: cluster center에 기반한 clustering 진행
- create a dataframe: image_id, image & mask 경로, cluster 정보가 포함된 dataframe 생성
- visualize the data: cluster(stainded, bright-field, fluorescence)에 따른 시각화 진행
- find and draw contours: 단일 mask에 대한 외곽선 정보 추출 연습
- get anotation information: 전체 mask의 polygon과 bounding box 정보를 추출하는 로직 함수화
- convert the dataset to COCO format: 추출된 annotation 정보를 활용해 COCO format으로 변환하는 로직 함수화
- visualize the data using pycocotools: COCO API를 활용해 instance segementation 시각화 진행
<img src="https://user-images.githubusercontent.com/109773795/183776882-572ee620-287c-4867-8b63-01ac0c32370c.png" width="950" height="150"/>
<img src="https://user-images.githubusercontent.com/109773795/183776651-838bf36e-336c-4bb2-86e0-2031f8f1a663.png" width="950" height="150"/>

####
#### ► [Afterthoughts]
- COCO dataset 변환 과정을 통해 COCO format의 annotation 정보를 상세히 학습할 수 있었습니다.
- 추출된 annotation 정보를 실제 instance segmentation에 적용해 볼 수 있어 매우 흥미로웠습니다.
####
#### ► [Reference]
- [[Kaggle] 2018 Data Science Bowl - Nucleus Segmentation](https://www.kaggle.com/competitions/data-science-bowl-2018)
####
