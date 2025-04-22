# 🚗 evq – Electric Vehicle Queue Predictor

EVQ는 전기차(EV) 사용자를 위한 **실시간 충전소 위치 및 대기시간 예측 앱**입니다.  
사용자는 현재 위치를 기반으로 주변 충전소를 지도에서 확인하고,  
AI 예측 기반으로 가장 효율적인 충전소를 선택할 수 있습니다.

---

## 🔍 프로젝트 목적

- ⚡ **전기차 충전소 대기 시간 예측**
- 📍 **현재 위치 기반 주변 충전소 시각화**
- ☁️ **날씨, 시간, 위치 데이터를 활용한 수요 모델링**
- 🧠 **AI 예측 백엔드 연동**
- 🗺️ **Naver Map SDK를 활용한 Android 지도 앱 구현**

---

## 🧱 기술 스택

| 영역 | 기술 |
|------|------|
| **Frontend** | 
| **Backend** | Spring Boot, PostgreSQL, REST API |
| **AI 예측 API** | 
| **지도 SDK** | [react-native-nmap](https://github.com/QuadFlask/react-native-nmap) (Naver 지도 Android SDK) |
| **지도 데이터** | 네이버 Developers 플랫폼 (CLIENT_ID 사용) |

---

## 📦 주요 기능

- [ ] Android 지도 위에 충전소 마커 표시
- [ ] 마커 클릭 시 충전소 정보 팝업
- [ ] 실시간 위치 추적 및 지도 중심 이동
- [ ] Spring 백엔드에서 충전소 목록 fetch
- [ ] Python Flask 기반 대기시간 예측 API 연동
- [ ] 날씨 API(OpenWeather or 기상청) 연동 예정
- [ ] 예측 정확도 향상을 위한 ML 모델 개선 예정