# 🥗 사전 학습 모델 VGG16, MobileNetV2를 활용한 Vegetable Image 분류 모델 연구 보고서

## 연구의 목적

본 연구의 목적은 야채 이미지 데이터셋을 활용하여 야채의 종류를 분류하는 모델을 개발하는 것이다. 이 데이터셋은 다양한 각도와 조명에서 촬영된 야채 이미지로 구성되어 있다. 총 15가지 종류의 야채로 구분되어 있다. 본 연구를 통해 이미지 분류 기술을 적용하여 야채 종류를 자동으로 식별하는 모델을 구축하고, 그 정확도를 평가하고자 한다.

본 연구에서는 아채 이미지 데이터셋의 분류 작업을 위해 사전 훈련 모델로 VGG16과 MobileNetV2를 선택하였다. 두 모델은 이미지 인식 분야에서 널리 활용되는 대표적인 합성곱 신경망(CNN)으로, 각기 다른 구조적 특징과 강점을 보유하고 있다. VGG16은 심층적인 구조를 바탕으로 복잡한 이미지 특성을 효과적으로 추출하여 높은 정확도를 나타내지만, 상대적으로 연산량이 많고 처리 속도가 느리다는 한계를 가진다. 반면 MobileNetV2는 경량화된 모델로서 모바일과 같이 제한된 환경에서도 높은 연산 효율을 제공하지만, 복잡한 이미지의 분류 정확도에서는 다소 한계를 드러낼 수 있다. 이러한 두 모델을 성능 및 효율성 측면에서 비교 분석하여 야채 이미지 데이터셋 분류 작업에 가장 적합한 모델을 도출하고자 한다.

---

## 데이터셋 설명

본 연구에 사용된 데이터셋은 Kaggle 플랫폼에 Misrak Ahmed가 공개한 ‘Vegetable Image Dataset’이다. 연구, 교육 등 다양한 목적으로 자유롭게 사용할 수 있도록 제공되고 있으며, 데이터셋의 원본 출처는 Kaggle에서 접근 가능하다(https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset/data). 야채 15종류를 포함한 21000개의 이미지로 구성된다. 모든 이미지는 224x224 픽셀로, JPG 형식으로 제공된다. 


