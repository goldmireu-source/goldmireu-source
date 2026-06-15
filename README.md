# goldmireu-source

AI 기반 자동화 도구를 개발하는 개인 개발자입니다.
Python · Flask · Claude API를 활용해 실제로 쓰는 서비스를 직접 만들고 운영합니다.

---

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

---

## Tech Stack

```
Languages   Python · HTML · JavaScript
Frameworks  Flask · APScheduler · SQLAlchemy
AI / LLM    Anthropic Claude · Google Gemini · Groq (Llama / Qwen)
Infra       Oracle Cloud · GitHub Actions · Cloudflare Tunnel · systemd
Tools       Playwright · BeautifulSoup4 · feedparser · fastembed (ONNX)
```

---

*270+ contributions · 3 public repos · joined May 2026*
