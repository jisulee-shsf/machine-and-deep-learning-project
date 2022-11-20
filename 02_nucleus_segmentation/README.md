####
## Objectives
- 가이드 강의를 참고해 스스로 코드를 작성하여 instance segmentation에 대한 심도있는 학습 진행
- 도메인 지식이 없는 분야의 주제를 선택하여, 새롭게 접하는 데이터 내에서 유의미한 insight를 찾는 분석 경험 축적
- Kaggle dataset을 핸들링 경험 축적
####
## Stack
-
    <div align="left"><img src="https://img.shields.io/badge/[ Python ]-NumPy / pandas / matplotlib / sklearn / cv2-4479A1"/>
    <img src="https://img.shields.io/badge/[ Computer vision ]-TensorFlow / OpenCV-FF6600"/>

-
    <div align="left"><img src="https://img.shields.io/badge/[ API ]-pycocotools-428813"/>
    <img src="https://img.shields.io/badge/[ Algorithm ]-K--Means Clustering-428813"/><br> 
####
## Timeline
- 220721~220727 - CV 관련 사전 실습 진행 > 'dl-cv-practice' repository 참고
- 220728~220730 - 도메인 파악을 위한 서칭 및 진행 pipeline 설정
- 220731~220801 - 1차 코드 작성 완료
- 220802 - 강사님과 피드백 면담 진행 / 최종 코드 작성 완료
- 220803~220804 - 발표자료 작성 및 제출
- 220805 - 발표 진행
####
## Contents
- Download the dataset - Kaggle API를 활용해 dataset 다운로드
- Explore the data - image / mask 경로 추출 로직 함수화 및 시각화 진행
- K-Means clustering - cluster center에 기반한 clustering 진행
- Create a dataframe - image_id / image & mask 경로 / cluster 정보 포함된 dataframe 생성
- Visualize the data - cluster(stainded & bright-field & fluorescence)에 따른 시각화 진행
- Find and draw contours - 단일 mask에 대한 외곽선 정보 추출 연습
- Get annotation information - 전체 mask의 polygon & bounding box 정보 추출 로직 함수화
- Convert the dataset to COCO format - 추출된 annotation 정보를 활용해 COCO format 변환 로직 함수화
- Visualize the data using pycocotools - COCO API를 활용해 instance segementation 시각화 진행
<img src="https://user-images.githubusercontent.com/109773795/183776882-572ee620-287c-4867-8b63-01ac0c32370c.png" width="950" height="150"/>
<img src="https://user-images.githubusercontent.com/109773795/183776651-838bf36e-336c-4bb2-86e0-2031f8f1a663.png" width="950" height="150"/>

####
## Afterthoughts
- COCO dataset 변환 과정을 통해 COCO format의 annotation 정보를 상세히 살펴볼 수 있었습니다.
- 추출된 annotation 정보를 바탕으로 instance segmentation 진행 과정을 심도있게 실습할 수 있었습니다. 
####
## Reference
- [[Kaggle] 2018 Data Science Bowl - Nucleus Segmentation](https://www.kaggle.com/competitions/data-science-bowl-2018)
####
