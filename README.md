# 날씨 & 미세먼지 대시보드 🌤️

실시간 날씨, 미세먼지, 초미세먼지 정보를 한눈에 확인할 수 있는 웹 대시보드입니다.

## 🌟 주요 기능

- **실시간 날씨 정보**: 현재 온도, 체감온도, 습도, 풍속, 기압
- **대기질 정보**: 미세먼지(PM10), 초미세먼지(PM2.5), 대기질 지수(AQI)
- **위치 기반**: 사용자의 현재 위치를 자동으로 감지
- **맞춤형 조언**: 날씨와 대기질에 따른 건강 및 생활 조언
- **반응형 디자인**: PC와 모바일 모두 최적화된 레이아웃

## 🚀 데모

[https://weather-dash-board-one.vercel.app/](https://weather-dash-board-one.vercel.app/)

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 반응형 디자인, 그라데이션, 애니메이션
- **JavaScript (ES6+)**: 비동기 API 호출, DOM 조작
- **OpenWeatherMap API**: 날씨 및 대기질 데이터

## 📦 설치 및 실행

1. 저장소 클론
```bash
git clone https://github.com/toonyman/WeatherDashboard.git
cd WeatherDashboard
```

2. 브라우저에서 `index.html` 파일 열기

또는 로컬 서버 실행:
```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 필요)
npx http-server
```

## 🔑 API 키 설정

OpenWeatherMap API 키가 필요합니다:

1. [OpenWeatherMap](https://openweathermap.org/api)에서 무료 API 키 발급
2. `index.html` 파일의 `OPENWEATHER_API_KEY` 변수에 키 입력

```javascript
const OPENWEATHER_API_KEY = 'YOUR_API_KEY_HERE';
```

## 📱 기능 상세

### 날씨 정보
- 현재 온도 및 날씨 상태
- 체감온도, 습도, 풍속, 기압
- 날씨 아이콘 (맑음, 흐림, 비, 눈 등)

### 대기질 정보
- AQI (대기질 지수): 1-5 단계
- PM10 (미세먼지) 농도
- PM2.5 (초미세먼지) 농도

### 맞춤 조언
- 온도별 대응법 (폭염, 한파 등)
- 날씨 상태별 조언 (비, 눈, 천둥번개)
- 습도별 건강 관리 팁
- 대기질별 행동 수칙

## 🎨 디자인 특징

- 모던한 그라데이션 배경
- 글래스모피즘 카드 디자인
- 부드러운 애니메이션 효과
- PC/모바일 반응형 레이아웃

## 📄 라이선스

MIT License

## 👤 작성자

Weather Dashboard Team

## 🙏 감사의 말

- [OpenWeatherMap](https://openweathermap.org/) - 날씨 및 대기질 데이터 제공
