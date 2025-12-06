<!--## Hi there 👋>

<!--
**cqb0709/cqb0709** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<h1 align="center"> 포트폴리오 </h1>


Cloud & Backend Engineer
Email: cqb0709@gmail.com | GitHub: https://github.com/cqb0709

🛠 Tech Stacks

| Category | Skills |
| --- | --- |
| **Backend & Cloud** | AWS (Lambda, API Gateway, DynamoDB, Cognito, GameLift, S3, IoT Core), Python |
| **DevOps** | GitHub Actions, CI/CD, AWS Amplify |
| **Embedded & IoT** | Arduino, ESP32, MQTT |
| **Tools & Others** | Docker, Git |


🚀 Projects

1. AWS Serverless 기반의 실시간 멀티플레이어 게임 백엔드 구축

Role: Backend Developer (AWS Infra & Server Logic)
Period: 2024.04 ~ 2024.06 (3개월)
Keywords: AWS GameLift, Serverless, CI/CD, Auto Scaling

[프로젝트 개요]
Unity 기반의 멀티플레이어 게임을 위한 고성능, 저비용 백엔드 서버를 구축했습니다. 유동적인 트래픽에 대응하고 운영 비용을 절감하기 위해 Serverless 아키텍처와 GameLift를 적극 활용했습니다.

[담당 역할 및 성과]

Serverless 백엔드 아키텍처 설계 및 구현

API Gateway와 AWS Lambda를 연동하여 서버 관리 부담이 없는 RESTful API 구축.

DynamoDB를 활용하여 유저 데이터 및 게임 로그의 초고속 읽기/쓰기 처리

보안 및 유저 관리 시스템

AWS Cognito User Pool을 활용하여 회원가입, 로그인, 토큰 기반 인증 로직 구현으로 보안성 강화.

비용 효율적인 게임 서버 호스팅

AWS GameLift Fleet 및 Auto Scaling 정책을 수립하여 트래픽에 따라 서버 인스턴스를 자동 증설/축소, 고정 비용 최소화.

GameLift FlexMatch를 도입하여 유저 랭킹 및 레이턴시 기반의 최적화된 매치메이킹 시스템 구현.

개발 생산성 향상 (CI/CD)

Github Actions와 AWS S3를 연동하여 코드 푸시 시 빌드 및 배포가 자동으로 이루어지는 CI/CD 파이프라인 구축.

2. IoT 기반 스마트 디바이스 제어 및 모니터링 웹 서비스

Role: Full Stack Developer (IoT Device & Web Integration)
Period: 202X.XX ~ 202X.XX
Keywords: AWS IoT Core, MQTT, ESP32, AWS Amplify

[프로젝트 개요]
ESP32 기반의 IoT 하드웨어와 웹 플랫폼을 연동하여 실시간으로 장치를 제어하고 데이터를 시각화하는 풀스택 프로젝트입니다.

[담당 역할 및 성과]

HW-SW 양방향 통신 구현

MQTT 프로토콜과 AWS IoT Core를 활용하여 ESP32 디바이스와 클라우드 간의 경량화된 실시간 메시징 시스템 구축.

Device Shadow를 활용하여 오프라인 상태에서도 명령을 동기화하도록 구현.

풀스택 웹 서비스 배포

AWS Amplify를 활용하여 프론트엔드 및 백엔드 리소스를 통합 관리하고 신속하게 웹 서비스 배포.

웹 대시보드에서 IoT 기기의 상태를 실시간으로 확인하고 원격 제어하는 기능 구현.

3. 풍력 발전기 마모 관측 AI 데이터 생성 및 모델링 (캡스톤 디자인)

Role: Hardware Engineer & Data Pipeline Architect
Period: 202X.XX ~ 202X.XX
Keywords: Hardware Control, Data Generation, Arduino, Computer Vision

[프로젝트 개요]
풍력 발전기의 유지보수를 자동화하기 위해 마모 상태를 탐지하는 AI 모델을 개발했습니다. 실제 데이터 확보의 어려움을 해결하기 위해 3D 프린팅 모형으로 시뮬레이션 환경을 구축하고 양질의 학습 데이터를 생성했습니다.

[담당 역할 및 성과]

데이터 생성을 위한 하드웨어 테스트베드 구축

3D 프린터로 풍력 발전기 축소 모형 제작 및 **마모 케이스(Crack, Erosion 등)**를 물리적으로 재현.

Arduino와 모터 드라이버(L298N 등), SMPS를 활용하여 발전기의 회전 속도(RPM)를 정밀 제어하는 회로 설계 및 배선.

다양한 RPM 환경에서의 영상 데이터를 확보하여 모델의 강건성(Robustness) 확보.

협업 파이프라인 최적화

생성팀(본인): 물리적 마모 데이터가 적용된 모형의 회전 영상 촬영 및 raw data 확보.

라벨링팀: SAM2(Segment Anything Model 2)를 활용하여 고정밀 COCO 포맷 라벨링 자동화 파이프라인 기여.

연구팀: 라벨링된 데이터를 기반으로 YOLOv8 모델 학습 및 마모 탐지 성능 검증.

문제 해결



🎓 Education & Activities

한국항공대학교 소프트웨어공학과 (2020.03 ~ 2026.02)


