## 황유 · Robot SW Engineer

계산한 궤적이 현장의 움직임이 되도록, **인식부터 제어기까지 직접 구현하고 데이터로 검증**하는 로봇 SW 엔지니어입니다.
한경국립대학교 ICT로봇공학전공 (2027.02 졸업 예정)

### Projects

| 프로젝트 | 내용 | 핵심 결과 |
|---|---|---|
| [**SCAR**](https://github.com/hyu07311/SCAR) | 비정형 계단 자율 청소 로봇 (졸업작품 · 3인 팀) — OpenCR 펌웨어, micro-ROS 통신, 상태 머신, 전원 설계, TensorRT 최적화 | 단차 17cm 등반 성공률 93.3% (30회 중 28회) · 한국지능로봇경진대회 우수상 |
| [**omy-motion-planner**](https://github.com/hyu07311/omy-motion-planner) | 6축 로봇팔 URDF 작성, IK · RRT-Connect · Cartesian 경로 C++ 구현, MoveIt과 비교 | IK 254.9 → 0.35 ms (약 730배) · 픽앤플레이스 20/20 충돌 0 |
| [**dynamixel-motor-monitor**](https://github.com/hyu07311/dynamixel-motor-monitor) | SDK 없이 Dynamixel Protocol 2.0 패킷 · CRC-16을 직접 구현한 C# 제어 · 모니터링 툴 | 50 ms 주기 모니터링 · SQLite 로깅 · MX-64 실기 검증 |

### Tech Stack

- **Language** Python · C++ (Eigen) · C#
- **Middleware** ROS 2 Foxy · Humble · micro-ROS
- **Robotics** MoveIt 2 · ros2_control · URDF · Gazebo · RViz
- **Embedded** OpenCR · Jetson AGX Xavier · Dynamixel Protocol 2.0
- **Vision** YOLOv8 · TensorRT · PyTorch

### Contact
yuhwang.hy@gmail.com
