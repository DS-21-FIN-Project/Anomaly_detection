![제목을-입력해주세요_-002](https://github.com/DS-21-FIN-Project/Anomaly_detection/assets/83691399/250d94bf-7b2d-4f0b-9afd-8919681deb4a)

### 프로젝트 개요
1. 프로젝트명: **동작 데이터를 활용한 폭행 및 쓰러짐 탐지 프로젝트**
2. 수행자: 강호진, 김소희
3. 수행 기간: 1개월 (2024.4.11 \~ 5.12)
4. 목표: 이 프로젝트의 목표는 동작 데이터를 활용하여 폭행 및 쓰러짐과 같은 비정상적인 행동을 신속하게 탐지하는 AI 모델을 개발하여, 학교 및 공공장소에서의 안전을 강화하고 사고 예방에 기여하는 것입니다. 이를 위해 YOLOv8 포즈 모델과 LSTM을 활용하여 골격 움직임 기반의 학습을 진행하고, 대규모 동작 데이터 수집을 통해 모델의 정확도를 높이며 실시간 동작 인식 시스템을 구현합니다 </br>
&nbsp;![asdasdasd](https://github.com/DS-21-FIN-Project/Anomaly_detection/assets/83691399/6c0c2b8e-25ce-44eb-b282-ec406ad30052)





# 동작 데이터를 활용한 폭행 및 쓰러짐 탐지 프로젝트

## 프로젝트 개요
- YOLO_pose의 동 분류와 LSTM 모델을 사용하여 한 손으로 장난감 블록을 조립하는 과정을 보조하는 AI 시스템입니다.

## 📎 파일 소개
- yolov8_pose와 OpenCV를 사용하여 실시간으로 사람의 골격의 좌표 데이터를 얻어오고, LSTM 모델에 보내 사람 둘 사이의 관계를 감지하여 화면에 표시합니다. 
- 사람의 동작( '싸우기', '쓰러짐', '서있기', '걷기')을 화면에 보여줍니다.
- YOLO pose를 사용해 인체의 골격 데이터를 추출하고 , 사람이 어떤 동작을 수행되는지 판단합니다.
  
## ⚡️ 실행 단계
- LSTM_TEST.ipynb 파일에서 데이터를 가공 및 학습을 진행 하였고 LSTM.ipynb 파일에서 실행 하였습니다.

## 👋 종료 방법
- 프로그램을 중간에 종료하려면, 'q' 키를 누릅니다.

## 🔥시연 영상

[![Video Label](http://img.youtube.com/vi/W1gfykFzkDc?si=EehAJtXZE8Aa-Gu9/0.jpg)](https://youtu.be/W1gfykFzkDc?si=EehAJtXZE8Aa-Gu9)
