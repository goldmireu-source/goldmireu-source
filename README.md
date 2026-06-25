# goldmireu-source

## Projects

### [cardnews-bot](https://github.com/goldmireu-source/cardnews-bot)
텍스트·이미지를 Telegram으로 보내면 Claude AI가 SNS 카드뉴스를 자동 생성하고 Instagram · Facebook · Threads에 예약 발행하는 자동화 파이프라인

- **Stack:** Python · Flask · Claude API · python-telegram-bot · APScheduler · Playwright
- **Features:** OCR 지원, 웹 편집 스튜디오, 멀티 채널 발행, 토큰 자동 갱신

### [dailysync](https://github.com/goldmireu-source/dailysync)
국내외 AI 뉴스를 매일 수집·클러스터링하고 LLM이 교차검증 요약한 한국어 다이제스트를 제공하는 큐레이션 서비스

- **Stack:** Python · Flask · SQLAlchemy · BGE-M3(ONNX) · Claude Haiku · GitHub Actions · Oracle Cloud
- **Features:** RSS 16개 소스, 임베딩 기반 클러스터링, 논문 트래킹, 공모전 수집, 자동 배포

### [studio-hub](https://github.com/goldmireu-source/studio-hub)
YouTube 음악 분석 및 AI 기반 한국어 가사 생성·번역 웹 애플리케이션

- **Stack:** Python · Flask · Groq API · Google Gemini · HTML/JS
- **Features:** 트랙 분석, 한국어 가사 생성, 다국어 번역, 오디오 다운로드

### [wildrift-counter](https://github.com/goldmireu-source/wildrift-counter)
Wild Rift 인게임 오버레이 지원 안드로이드 앱 — 148챔피언 카운터 정보 검색 및 포지션 필터

- **Stack:** Kotlin · Android (minSdk 26) · Gradle KTS · Material Design · Glide · WindowManager
- **Features:** 챔피언 이름/포지션 필터 검색, 148챔피언 카운터 DB, 인게임 플로팅 오버레이

### [traffic-signal-optimizer](https://github.com/goldmireu-source/traffic-signal-optimizer)
Python으로 구현한 실시간 교통 시뮬레이션 및 신호 최적화 분석 시스템 — 강남역 실제 도로망 기반 4가지 신호 전략 비교 및 멀티에이전트 AI 자율 제어

- **Stack:** Python · pygame · numpy · networkx · osmnx · scipy · matplotlib
- **Features:** IDM 차량 모델, 4전략 비교(Fixed/Actuated/GA/DQN), 멀티에이전트 AI, OSM 실제 도로망, 실시간 GUI

---

## Tech Stack

```
Languages   Python · HTML · JavaScript · Kotlin
Frameworks  Flask · APScheduler · SQLAlchemy
AI / LLM    Anthropic Claude · Google Gemini · Groq (Llama / Qwen)
Infra       Oracle Cloud · GitHub Actions · Cloudflare Tunnel · systemd
Tools       Playwright · BeautifulSoup4 · feedparser · fastembed (ONNX)
```
