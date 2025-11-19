# 🌱 베란다 농부 (Balcony Farmer)

<div align="center">

<img width="432" height="126" alt="Frame 6" src="https://github.com/user-attachments/assets/8334f8f1-eea8-4115-9479-7134020c39b3" />


**스마트팜 IoT 시스템으로 누구나 쉽게 작물을 재배할 수 있습니다**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/dadadadamin/minifarm)
[![Swagger](https://img.shields.io/badge/Swagger-API_Docs-85EA2D?logo=swagger&logoColor=black)](https://petstore.swagger.io)

</div>

---

## 📑 목차
- [프로젝트 소개](#-프로젝트-소개)
- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [시스템 아키텍처](#-시스템-아키텍처)
- [팀원 소개](#-팀원-소개)
- [개발 환경](#%EF%B8%8F-개발-환경-및-ide)
- [시작하기](#-시작하기)
- [주요 구현 사항](#-주요-구현-사항)
- [트러블슈팅](#-트러블슈팅)

---

## 💡 프로젝트 소개

**베란다 농부**는 도심 속 베란다에서 스마트하게 작물을 재배할 수 있도록 돕는 IoT 기반 스마트팜 시스템입니다.

### 개발 배경
- 1인 가구 증가로 인한 홈 가드닝 수요 증가
- 초보자도 쉽게 작물을 재배할 수 있는 시스템 필요
- IoT 센서와 자동화로 최적의 재배 환경 제공

### 진행 기간
**2024.10.01 ~ 2024.11.28** (9주)

---

## ✨ 주요 기능

### 1. 실시간 환경 모니터링 📊
- 온도, 습도, CO2, EC, 조도, 토양 수분 실시간 측정
- 센서 데이터 시각화 대시보드

### 2. 원격 장치 제어 🎮
- 워터 펌프 자동/수동 제어
- LED 조명 On/Off 및 밝기 조절
- 환풍기 제어로 환기 관리
- WebSocket 기반 실시간 제어

### 3. 작물 생육 관리 🌿
- 작물별 최적 환경 조건 제공
- 생육 단계별 관리 가이드
- 작물 성장 기록 및 사진 저장

### 4. STT/TTS 기반 스마트팜 관리 및 제어 🗣️
- 마음 AI Suda Kit를 이용한 STT/TTS 기능
- 음성 인터페이스를 이용한 기기제어, 센서 데이터 관리

### 5. 자동화 규칙 설정 ⚙️
- 조건 기반 자동 제어 (예: 토양 수분 30% 이하 시 자동 관수)

### 6. 알림 및 통계 📱
- 이상 환경 감지 시 Push 알림
- 일/주/월 단위 환경 통계
- 작물별 생육 분석 리포트

### 7. 식물 성장 다이어리 📅
- 식물의 사진과 설명을 캘린더에 기록하여 다양한 인터랙션 제공
- 업로드한 식물 사진을 타임랩스로 기록

### 8. AI식물 진단 💊
- 스마트팜 카메라를 이용한 식물 사진 촬영과 식물 사진 기반 open vision api를 활용한
  병해충 진단 및 식물 건강 진단

---

## 🛠 기술 스택

### Backend
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/>

### Frontend
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white"/>

### IoT / Hardware
<img src="https://img.shields.io/badge/SudaKit-FF6B6B?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/> <img src="https://img.shields.io/badge/Mosquitto-3C5280?style=flat-square&logo=eclipsemosquitto&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>

**센서 목록**
- DHT22 (온습도 센서)
- MH-Z19B (CO2 센서)
- EC 센서 (전기전도도)
- BH1750 (조도 센서)
- 토양 수분 센서

### Server & DevOps
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/> <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>

### Cooperation & Communication
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"/>

---

## 🏗 시스템 아키텍처

```
┌─────────────┐         ┌──────────────┐         ┌─────────────┐
│   Frontend  │◄───────►│   Backend    │◄───────►│  Database   │
│   (React)   │  HTTPS  │ (Spring Boot)│   JDBC  │ (PostgreSQL)│
└─────────────┘         └──────────────┘         └─────────────┘
                               ▲
                               │ WebSocket
                               │ (MQTT)
                               ▼
                        ┌──────────────┐
                        │  Raspberry   │
                        │      Pi      │
                        └──────────────┘
                               ▲
                               │ GPIO/I2C
                               ▼
                    ┌─────────────────────┐
                    │  IoT Sensors        │
                    │  - Temperature/     │
                    │    Humidity         │
                    │  - CO2, EC, Light   │
                    │  - Soil Moisture    │
                    └─────────────────────┘
```
<img width="1591" height="863" alt="스크린샷 2025-11-14 오후 7 04 15" src="https://github.com/user-attachments/assets/eacfaf93-10c7-421d-b2f5-a3fe44c9b3c0" />
---

## 👥 팀원 소개

| 이름 | 역할 | GitHub | 담당 업무 |
|------|------|--------|-----------|
| 황필호 | Backend | [@github](https://github.com) | 머신러닝, IoT 개발, 라즈베리파이 개발 |
| 이다민 | Backend | [@github](https://github.com) | 서버 구축, 기능 구현, DB설계 |
| 김윤호 | Frontend | [@github](https://github.com) | UI/UX 개발, IoT 개발 |

---

## ⚙️ 개발 환경 및 IDE

### Backend
- **Language** : Java 17
- **Framework** : Spring Boot 3.1.5
- **Build Tool** : Gradle 8.3
- **IDE** : IntelliJ IDEA 2023.2

### Frontend
- **Language** : TypeScript 5.2
- **Framework** : React 18.2
- **Build Tool** : Vite 4.5
- **IDE** : VS Code

### IoT
- **Language** : Python 3.9
- **Platform** : Raspberry Pi 4 Model B
- **IDE** : VS Code

### Server
- **OS** : Ubuntu 22.04 LTS
- **Web Server** : Nginx 1.18
- **Database** : PostgreSQL 15

---

## 🚀 시작하기

### 📋 사전 요구사항
- Java 17+
- Node.js 18+
- PostgreSQL 15+
- Raspberry Pi (IoT 기능 사용 시)

### 1️⃣ Backend 실행

```bash
# 레포지토리 클론
git clone https://github.com/dadadadamin/minifarm.git
cd minifarm

# 환경 변수 설정
cp application.yml.example application.yml
# application.yml 파일을 열어 DB 정보 등 설정

# 빌드 및 실행
./gradlew clean build
./gradlew bootRun
```

서버가 `http://localhost:8080`에서 실행됩니다.

### 2️⃣ Frontend 실행

```bash
# 프론트엔드 레포지토리 클론
git clone https://github.com/VerandaFarmer/FE.git
cd FE

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

프론트엔드가 `http://localhost:5173`에서 실행됩니다.

### 3️⃣ IoT 센서 연결 (선택사항)

```bash
# Raspberry Pi에서 실행
git clone https://github.com/VerandaFarmer/IoT.git
cd IoT

# Python 의존성 설치
pip install -r requirements.txt

# 센서 스크립트 실행
python main.py
```

---

## 🔧 주요 구현 사항

### 1. JWT 기반 인증 시스템
- Spring Security와 JWT를 활용한 stateless 인증
- Access Token(1시간) + Refresh Token(7일) 구조
- Token 재발급 API 구현

```java
@PostMapping("/refresh")
public ResponseEntity<TokenResponse> refresh(@RequestBody TokenRequest request) {
    return ResponseEntity.ok(authService.refreshToken(request.getRefreshToken()));
}
```

### 2. WebSocket 실시간 통신
- STOMP 프로토콜을 사용한 양방향 통신
- 센서 데이터 실시간 Push
- 장치 제어 명령 즉시 반영

```java
@MessageMapping("/device/control")
@SendTo("/topic/device")
public DeviceStatus controlDevice(DeviceCommand command) {
    return deviceService.control(command);
}
```

### 3. 센서 데이터 처리 파이프라인
- Raspberry Pi에서 센서 데이터 수집 (1분 주기)
- MQTT 프로토콜로 백엔드 서버 전송
- 데이터 검증 및 DB 저장
- 이상치 감지 알고리즘 적용

```python
def read_sensors():
    data = {
        'temperature': dht22.temperature,
        'humidity': dht22.humidity,
        'co2': mhz19.read(),
        'ec': ec_sensor.read(),
        'light': bh1750.measure_light(),
        'soil_moisture': soil_sensor.read()
    }
    mqtt_client.publish('sensor/data', json.dumps(data))
```

### 4. 자동화 규칙 엔진
- Rule Builder 패턴으로 유연한 규칙 생성
- Cron 표현식 기반 스케줄링
- 조건부 실행 로직

```java
AutomationRule rule = AutomationRule.builder()
    .condition(Condition.lessThan("soilMoisture", 30.0))
    .action(Action.turnOn("WATER_PUMP", 180))
    .build();
```

### 5. 데이터 시각화
- Recharts 라이브러리로 실시간 차트 구현
- 시계열 데이터 최적화 렌더링
- 반응형 대시보드 디자인

---

## 🐛 트러블슈팅

### 1. 센서 데이터 손실 문제
**문제**: Raspberry Pi에서 전송한 센서 데이터가 간헐적으로 손실됨

**원인**: 네트워크 불안정 시 MQTT 연결 끊김

**해결**:
- 로컬 SQLite DB에 데이터 임시 저장
- 재연결 시 미전송 데이터 일괄 전송
- Keep-alive 설정으로 연결 유지

```python
# 연결 실패 시 재시도 로직
def on_disconnect(client, userdata, rc):
    if rc != 0:
        while True:
            try:
                client.reconnect()
                break
            except:
                time.sleep(5)
```

### 2. WebSocket 연결 타임아웃
**문제**: 사용자 비활성 시 WebSocket 연결이 자동으로 끊김

**해결**:
- Heartbeat 메시지로 연결 유지 (30초 주기)
- Nginx의 proxy_read_timeout 설정 조정

```nginx
location /ws {
    proxy_pass http://backend;
    proxy_read_timeout 3600s;
    proxy_send_timeout 3600s;
}
```

### 3. 대용량 센서 데이터 조회 성능 이슈
**문제**: 한 달치 센서 데이터 조회 시 응답 속도 저하

**해결**:
- 시계열 데이터에 적합한 인덱스 추가
- 데이터 집계 후 전송 (1분 단위 → 10분 평균)
- Redis 캐싱 적용

```sql
-- 복합 인덱스 생성으로 조회 성능 개선
CREATE INDEX idx_sensor_time ON sensor_data(sensor_type, timestamp DESC);
```

---

## 📊 서버 포트 구성

| Port | 용도 | 설명 |
|------|------|------|
| 80 | HTTP | HTTPS로 리다이렉트 |
| 443 | HTTPS | Nginx (Frontend) |
| 8080 | Backend | Spring Boot API |
| 5432 | Database | PostgreSQL |
| 1883 | MQTT | IoT 센서 통신 |

---

## 📝 API 문서

👉 **[Notion 개발일지 바로가기](https://www.notion.so/2798e86a04c38065a111eaceb655d90d?source=copy_link)**

👉 **[Swagger API 문서 바로가기](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/dadadadamin/minifarm/main/swagger.yaml)**

---

## 📷 스크린샷

### 대시보드
![대시보드](https://via.placeholder.com/800x450/4CAF50/FFFFFF?text=Dashboard)

### 장치 제어
![장치제어](https://via.placeholder.com/800x450/2196F3/FFFFFF?text=Device+Control)

### 작물 관리
![작물관리](https://via.placeholder.com/800x450/FF9800/FFFFFF?text=Plant+Management)


---

## 🙏 감사의 말

이 프로젝트는 한성대학교 컴퓨터공학부 졸업 프로젝트로 진행되었습니다.

---

<div align="center">

**⭐ Star를 눌러주시면 프로젝트 개발에 큰 힘이 됩니다!**

Made with ❤️ by Balcony Farmer Team

</div>
