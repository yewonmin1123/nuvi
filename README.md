# NUVI — 2026 제품디자인 졸업전시

단안경과 스마트 밴드로 숲을 탐험하는 아이를 위한 곤충 도감 앱.

| 페이지 | 파일 |
|---|---|
| 첫 화면(목차) | index.html |
| 브랜드 사이트 | brand.html |
| 앱 가로형 | app-wide.html |
| 전시용 맥북 | mac.html |
| 전시용 아이패드 | ipad.html |
| 휴대폰용 앱 | phone.html |

모든 그림 · 글꼴 · 스크립트가 파일 안에 들어 있어 오프라인에서도 열린다.
포함된 오픈소스: GSAP 3.15 · Draggable · InertiaPlugin · MotionPathPlugin · CustomEase · CustomBounce · CustomWiggle (GreenSock standard license, https://gsap.com/standard-license)


카메라 모드(`viewfinder.html?cam`)는 [MediaPipe Tasks Vision](https://github.com/google-ai-edge/mediapipe) 0.10.35와 Pose Landmarker(lite) · Gesture Recognizer 모델(Apache-2.0)을 `mp/`에 담아 브라우저 안에서만 돌립니다. 카메라 영상은 저장하거나 보내지 않습니다.
감도 보정: `viewfinder.html?calib` (결과는 그 브라우저에 저장).
