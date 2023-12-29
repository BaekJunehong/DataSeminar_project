# DataSeminar_project

<img src="https://github.com/BaekJunehong/DataSeminar_project/assets/101456289/489e6d9e-6608-4049-b4c3-6ea222fcbb19" alt="image" width="600" height="300">

## 1. 프로젝트 개요  
- [23.10.24~23.12.19] 기간동안 진행
  
2023년 2학기 통계학과 수업인 데이터사이언스 세미나 수업으로 진행한 프로젝트로 수업때 배운 CNN 이미지 분류, 차원축소를 통한 시각화 이 2가지 과정에 대해 
인상적으로 느껴 이번 기말과제를 통해 구현해보며 개념에 대한 심화학습 진행을 목표   

위의 내용을 접목할 수 있는 프로젝트로 개 품종 분류를 주제로 선정하였고, 개 품종 간에도 특성들이 다양한데 이러한 부분에 있어 사람의 눈보다 딥러닝 기술이 더 잘 분류할 수 있지 않을까 하는 생각에 프로젝트를 구상  

<img src="https://github.com/BaekJunehong/DataSeminar_project/assets/101456289/b0740045-6190-46a8-a098-c234b4ca9af5" alt="image" width="500" height="200">

데이터의 경우 Kaggle의 개 품좀 분류(Dog Breed Identification) 데이터를 이용

## 2. 프로젝트 과정  

1) k-mean 클러스터링 기법 및 t-SNE를 활용한 이미지 특성 시각화
    
- CNN 모델에서 추출한 이미지 특성을 활용하여 클러스터링 기법을 활용하여 품종 120종에 대하여 군집화를 진행
- 각 군집 별로 대표 품종을 선택 및 군집화가 잘 진행되었는지 확인을 위해 t-SNE를 통해 시각화를 진행
  
2) CNN 모델을 활용한 이미지 분류
  
- 선정된 대표종을 기반으로 CNN을 활용한 이미지 분류 모델을 생성

## 3. 모델 적용 예시

<img src="https://github.com/BaekJunehong/DataSeminar_project/assets/101456289/0df2dd0c-3f40-497a-912b-5c989e0af938" alt="image" width="700" height="350">
<img src="https://github.com/BaekJunehong/DataSeminar_project/assets/101456289/60cd09f7-5d7b-473f-8d13-c9818b0b325f" alt="image" width="700" height="350">


## 4. 맺음글
품종 간 유사도 차이가 큰 개 품종들을 중점적으로 선정하여 모델을 구현함으로써, 모든 품종을 고르게 사용하거나 상위 20개 품종에 집중하는 일반적인 방식보다 더 높은 분류 성능을 달성하는 것을 목표로 진행하였는데 목표했던 바에 도달한 거 같고 CNN 모델을 처음 사용하여 보는데 이를 이번 프로젝트를 통해 구현해 볼 수 있는 기회를 가지게 되어 좋았던 거 같습니다.



