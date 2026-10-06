### 임성민 · Sungminlim1020
Software Developer | Android · Backend · AI

평택대학교 스마트콘텐츠학과 — 프로젝트를 직접 만들면서 문제를 찾고 해결하는 과정에 관심이 많습니다.

---

### Tech Stack

**Languages**
`Kotlin` `Java` `C++` `Python`

**Backend / Database**
`Firebase` `MySQL`

**AI / ML**
`TensorFlow Lite` `MoveNet`

**Tools**
`Git` `GitHub` `Android Studio` `VS Code`

---

### Featured Projects

**[SmartBulk](https://github.com/sungminlim1020/SmartBulk-app)**  
AI 기반 개인 맞춤 운동 추천 및 자세 피드백 Android 애플리케이션

Kotlin으로 개발한 Android 앱으로, TensorFlow Lite MoveNet을 이용한 온디바이스 자세 인식과 Firebase (Authentication / Realtime Database / Cloud Functions), Anthropic Claude API를 활용했습니다.

초기 수업 프로젝트에서는 자세 인식이 안정적으로 동작하지 않는 문제가 있었습니다. 처음에는 각도 임계값 문제로 판단했지만, 다시 분석해보니 카메라 프레임 회전 보정과 YUV 변환, TFLite 입력 처리 과정에 원인이 있었습니다. 이를 바탕으로 카메라/모델 추론과 운동별 판정 로직을 분리하고, 단일 임계값 대신 운동별 상태 머신 방식으로 구조를 다시 설계했습니다.

- 운동 종류별 자세 판정 로직 (10종)
- 연습 모드 / 날짜 기반 운동 계획 / 오늘의 운동 체크리스트
- Firebase Cloud Functions를 통한 AI 식단 추천 (API 키는 서버에서만 관리)

**[CodiShoes](https://github.com/sungminlim1020/CodiShoes)**  

AI 기반 개인 맞춤형 신발 추천 및 코디 관리 Android 애플리케이션

Kotlin과 Android를 기반으로 개발했으며, 사용자의 스타일·색상·가격대·착용 상황 등을 바탕으로 AI 신발 추천 기능을 구현했습니다. 추천 결과를 코디로 저장하고 관리할 수 있으며, 신발 정보와 사용자 데이터를 관리하는 백엔드 및 데이터베이스 연동을 경험했습니다.

Tech: Kotlin Android Firebase MySQL AI API GitHub

---

### Currently Learning

Backend Development · Database · Linux · Cloud · AI · ChatGPT

---

