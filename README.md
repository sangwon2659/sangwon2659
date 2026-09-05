# 안녕하세요 👋

로보틱스·비전 소프트웨어 엔지니어 **이상원**입니다. 삼성전자 **Robotics AI Team (RX)** 에서 휴머노이드 로봇의 비전과 정책 학습 소프트웨어를 개발하고 있습니다. 촉각 센싱과 제어 연구에서 시작해 산업 현장의 로봇 비전 시스템을 거쳐, 지금은 VLA (Vision-Language-Action) 정책을 다루고 있습니다.

[CV](https://sangwon2659.github.io/cv/) · [LinkedIn](https://www.linkedin.com/in/s-won-lee/) · [Email](mailto:sangwon2659@gmail.com)

## 🤖 경력

**Vision & Policy Software Engineer, Humanoid Robotics**
삼성전자 Robotics AI Team (RX), 서울 · 2026.01 – 현재

- Learned projector 기반 multi-modal VLA fusion 아키텍처 설계 및 multi-node GPU 클러스터 학습
- 양팔 매니퓰레이션을 위한 offline advantage-conditioned policy post-training, RL-for-VLA 조사
- 실시간 정책 실행 속도 가속 — 방법론 서베이부터 실제 로봇 배포까지
- Time-warped demonstration 기반 속도 증강 학습, 학습 데이터 품질 진단
- Custom keypoint head를 붙인 detection, 신뢰성이 중요한 구간을 위한 classical computer vision

**Robot & Quality Control Vision System Engineer**
삼성전자 Visual Display, 제조기술그룹, 수원 · 2022.09 – 2026.01

- Bin-picking 비전 — structured-light 3D 취득, instance segmentation, pick 선정, grasp pose 추정
- Palletizing 비전 — ToF depth 기반 박스 검출, 3D 위치 추정, 적재 패턴 자동 생성
- 산업용 로봇 2D 위치 보정 — 자체 hierarchical template matching과 camera-to-robot calibration, 단일 PC로 다수 로봇·카메라 동시 구동
- Marker 기반 stereo vision 3D 위치 추정, 양산 라인에 배포된 딥러닝 외관 검사 시스템

## 🎓 학력

**연세대학교 기계공학과 석사** · 2020 – 2022

- 정밀제어시스템연구실 (Mservo Lab), 지도교수 양현석
- 학위논문 — 수직항력 센서 어레이만을 이용한 로봇 그리퍼 미끄러짐 검출 알고리즘
- 손 모양 외골격과 원격 로봇 팔을 연결한 양방향 힘 피드백 원격조작 시스템 구축

**연세대학교 기계공학과 학사** · 2014 – 2020

## 📄 논문

- H. Bamshad, **S. Lee**, K. Son, H. Jeong, G. Kwon, H. Yang. "Multilayer-perceptron-based Slip Detection Algorithm Using Normal Force Sensor Arrays." *Sensors and Materials* 35(2), 365–376, 2023.
- **S. Lee**, W. Jeon, K. Son, H. Yang. "Object Slip Detection Algorithm with the Sole Use of Normal Reaction Force Data." 대한기계학회 호남지부 학술대회, 포스터, 2021.

## 🧰 다루는 기술

| | |
|---|---|
| **모델 · 아키텍처** | VLA fusion architecture · YOLO11 · Mask2Former · DETR · SigLIP |
| **정책 학습 · 실시간 실행** | advantage-conditioned policy learning · diffusion-steering RL · Real-Time Chunking · asynchronous inference · 최적화 기반 action post-processing · multi-node distributed training |
| **비전 알고리즘** | homography estimation · RANSAC variants · Direct Linear Transformation · hierarchical template matching · camera-to-robot calibration |
| **제어 · 기구학** | LQR · LQG · MRAC · MPC · Kalman filter · 순·역기구학 · path planning |
| **프레임워크 · 라이브러리** | PyTorch · Hugging Face Transformers · LeRobot · OpenCV · ROS / ROS2 |
| **하드웨어 · 인터페이스** | structured-light / ToF / stereo 카메라 · KUKA 산업용 로봇 · Robotis Dynamixel · I2C · SPI · TCP/IP · Modbus · CAN · PLC |

## 💻 사용하는 언어와 도구

[![Languages and tools](https://skillicons.dev/icons?i=cpp,c,cs,python,linux,docker,git,visualstudio,dotnet,matlab,cmake,arduino,unity&perline=20)](https://skillicons.dev)

🇰🇷 한국어 (모국어) · 🇺🇸 영어 (OPI: Superior)

<!--
**sangwon2659/sangwon2659** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
