# YOLOv8을 활용한 도로 포트홀 탐지

도로 위의 포트홀(pothole)을 YOLOv8 기반 객체 탐지 모델로 학습하고, 실제 이미지에 대한 탐지 결과를 시각화했습니다.

## Model
YOLOv8 (Ultralytics)

## Dataset
roboflow에서 1338장의 pothole detection 데이터셋

## Result
정확도 (Precision): 0.862
재현율 (Recall): 0.821
mAP@0.5: 0.899

## Code
yolov8n을 통해 학습 진행
epoch 10에서 성능이 상승률이 정체되지않아 epoch 20으로 다시 학습

epoch 수에 따른 Precision과 Recall 결과 비교 그래프를 통해 시각화

Detection 결과를 확인하기 위해 예시 이미지 2개를 통해 bounding box와 그 확률을 확인해볼 수 있다
