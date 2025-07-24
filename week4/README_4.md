# Yolov8을 활용한 American Sign Language를 객체 탐지 후 한국어로 번역

## model
Yolov8(yolov8n.pt)

## dataset
1728장의 American Sign Language Letters Dataset

## 성능
best.pt의 Precision과 Recall 값 시각화

## detection
이미지 경로를 지정해 yolov8 모델 성능 확인

## 단어 생성
리스트에 단어 이미지 분석 결과를 저장해 붙임

## 번역
googletrans API로 단어를 한국어로 번역
후 시각화
