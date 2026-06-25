# 👾 이지상 (Jisang Lee)

실시간 미디어·온디바이스 비전 파이프라인을 직접 설계·구현하는 **Android 엔지니어**입니다.
기획부터 배포·운영까지 제품을 끝까지 책임진 경험이 있고, CameraX·OpenGL ES·MediaCodec
저수준 미디어 처리부터 MPEG-TS/SRT 송출 규격 직접 구현까지 다룹니다.

- 📱 Android · 실시간 미디어 / 온디바이스 Vision
- 🧑🏻‍💻 모델·렌더링·송출 제약을 함께 설계하는 시스템 엔지니어링에 관심

---

## 대표 프로젝트

### 🎥 [FOCUS — 온디바이스 얼굴 보호·실시간 스트리밍](https://github.com/KMU-FOCUS/focus-android)
IRL 스트리밍 중 제3자 얼굴만 단말에서 실시간 보호한 뒤 송출하는 Android 클라이언트 · 팀장/Android 전담
- CameraX → OpenGL ES → MediaCodec → MPEG-TS/SRT 실시간 파이프라인 직접 구현
- YuNet·ArcFace·3DMM 온디바이스 통합, 분석 지연 평균 34ms / p95 54ms (S25·1080p)
- MPEG-TS/PES subset·PTS 동기화 직접 구현, 약 7시간 무중단 방송
- 다학제간캡스톤디자인 우수상

### 🩺 [Probodia — 당뇨 관리](https://github.com/jisang0706/probodia-android)
혈당·식단·복약 기록과 음식 당뇨 지수 분석을 묶은 당뇨 관리 앱 · Android 1인 전담 (SW Maestro 13기)
- Google Play 배포·운영, 누적 2,096명 · 의료 카테고리 최고 15위
- 5개 API 경계 분리, 토큰 갱신·Crashlytics 기반 운영 안정화

---

## 🛠 Tech Stack

- **Language / UI:** Kotlin, Jetpack Compose, Android Views/XML
- **Architecture:** Multi-module, MVVM, Clean Architecture, Hilt, Coroutines, Flow/StateFlow
- **Graphics / Media:** CameraX, OpenGL ES, MediaCodec, OES Texture, EGL Thread
- **AI / Vision:** OpenCV(YuNet), ArcFace, 3DMM, TensorFlow Lite, ONNX Runtime
- **Network / Streaming:** Retrofit, OkHttp, gRPC, Protobuf, MPEG-TS, SRT

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jisang0706&layout=compact&theme=radical)](https://github.com/jisang0706)
