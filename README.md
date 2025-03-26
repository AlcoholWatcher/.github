# AlcoholWatcher

🚗 **AlcoholWatcher**는 음주운전 방지를 위한 시스템으로, 사용자의 혈중알코올농도를 측정하고 차량 시동을 제어하는 기능을 제공합니다.

## 📌 주요 기능
- **실시간 혈중알코올농도 측정**: 센서를 통해 사용자의 혈중알코올농도를 감지
- **차량 시동 제어**: 알코올 수치가 기준치를 초과하면 차량 시동 차단
- **운전자 데이터 기록**: 운전자의 음주 여부 및 운전 기록 저장
- **모바일 앱 연동**: 경고 알림 및 데이터 확인 기능 제공

## 🛠 기술 스택
- **하드웨어**: 알코올 센서 (MQ-3 등)
- **임베디드 시스템**: Raspberry Pi / Arduino
- **백엔드**: Python (Flask, FastAPI)
- **프론트엔드**: React Native (모바일 앱)
- **데이터베이스**: PostgreSQL

## 🚀 설치 및 실행 방법
### 1. 프로젝트 클론
```bash
git clone https://github.com/your-repo/AlcoholWatcher.git
cd AlcoholWatcher
```

### 2. 백엔드 서버 실행
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 3. 프론트엔드 실행
```bash
cd frontend
npm install
npm start
```

## 📄 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.

## 📞 문의
이슈 등록 또는 이메일로 문의해 주세요: `your.email@example.com`
