<div align="center">

# 👋 Sejong Jang (Toma)

**AI / Data Engineer**

Building **On-Premise LLM Systems · RAG Pipelines · Agentic Development**

폐쇄망·공공 환경에서 **LLM 서비스를 설계하고 운영 배포**합니다.<br>
수집(ETL)부터 데이터셋 생성, RAG, 온디바이스 AI까지 **AI 서비스 전 주기**를 다룹니다.

</div>

---

## 🧠 About Me

- **폐쇄망(air-gapped) 온프레미스 RAG 챗봇** 설계 → 구축 → 운영 배포 (공공기관 납품)
- **FastAPI + Next.js + PostgreSQL/Qdrant** 기반 LLM SaaS 풀스택 개발
- **온디바이스 AI**: Flutter + Gemma 온디바이스 추론 (LiteRT)
- **AI 데이터 파이프라인**: 멀티소스 수집·정제 → PDF→QnA 데이터셋 생성 → LLM Judge 평가
- **보안 자동화**: KISA 기술 취약점 가이드 기반 진단·조치 플랫폼
- **Claude Code 기반 Agentic 개발 환경** 구축 (멀티에이전트 리뷰·훅·자동화)

---

## ⚙️ Tech Stack

**Programming**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>, <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>, <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>

**AI / LLM**

<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemma-4285F4?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG%20%7C%20bge--m3%20%7C%20BM25%2BRRF-121D33?style=flat-square"/>

**Backend / Frontend**

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>

**Data / Infra**

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes(k3s)-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux%20%2F%20WSL2-FCC624?style=flat-square&logo=linux&logoColor=black"/>

---

## 🚀 Featured Projects (2026)

> 업무 특성상 대부분 private / 사내 저장소입니다. 문의 주시면 소개 가능한 범위에서 설명드립니다.

| 프로젝트 | 소개 | 핵심 기술 | 상태 |
|---|---|---|---|
| **여권 헬프데스크 RAG 챗봇** | 폐쇄망 단일 Docker 컨테이너 온프레미스 RAG — 하이브리드 검색(bge-m3 + 형태소 BM25 + RRF), PII 필터·안전 게이트, PDF 출처 하이라이트 | FastAPI · Ollama(Gemma) · SQLite VectorStore · Vue 3 | ✅ 운영 배포 |
| **온기 (ONGI)** | 디지털 취약계층을 위한 온디바이스 AI 스마트폰 접근성 도우미 — 앱 자동 분류 런처, 음성 명령, 생활 루틴 추천 (2026 오픈소스 개발자대회 출품) | Flutter · Gemma 4 E2B on-device · LiteRT-LM | 🏗 개발 중 (제출 시 공개) |
| **biz-radar** | 정부지원사업 공고 7개 소스 일일 자동 수집 + 시맨틱 임베딩 매칭 큐레이션 SaaS | FastAPI · Next.js 15 · PostgreSQL · Qdrant | ✅ 사내 운영 |
| **돋움 (dodum)** | 보험설계사 영업 트레이닝 — AI 가상고객 롤플레이, 루브릭 자동평가, 발음 명료도(GOP) 분석, 상품문서 사실검증 | Next.js · Ollama · wav2vec2 · CosyVoice2 | 🧪 POC |
| **Ai-Fin** | 중소기업 재무 자동화 AI 플랫폼 — 4-모델 패밀리 설계, 4중 품질 게이트 데이터 파이프라인, 프라이버시 보존 학습 (30개월 국책 R&D) | Python · LangGraph · ChromaDB · vLLM | 🏗 개발 중 |
| **VulnAgent** | KISA 기술 취약점 가이드 기반 진단·조치 자동화 데스크톱 플랫폼 — 11개 분야 확장형 에이전트 아키텍처(Unix·Windows 우선 구현), 실시간 스트리밍 UI | PySide6 · Bash/PowerShell 에이전트 · SQLite | 🏗 개발 중 |
| **qna-dataset-generator** | PDF→QnA 데이터셋 6단계 파이프라인 — 시맨틱 청킹, LLM Judge 평가, ROUGE 중복·과복사 검증, 멀티호스트 GPU 병렬 | Python · Ollama · pdfplumber | ✅ 완료 (7,800+ QnA) |
| **[claude_dashboard](https://github.com/jangsejong/claude_dashboard)** | Claude Code 팀 토큰 사용량 대시보드 — 로컬 JSONL 로그 파싱 기반 증분 수집·멱등 적재·시각화 | FastAPI · PostgreSQL · Grafana | ✅ 팀 운영 |
| **AI Usage Hub** | 전사 AI/LLM 사용량 통합 모니터링 — 2계층 수집(Admin API + LiteLLM 게이트웨이), Shadow AI 가시화, 인원 단위 비용 집계 | FastAPI · Next.js · LiteLLM | 🧪 POC |

이 외에도 **의약품 안전성(약물감시) 솔루션 설계**(FHIR/HL7/MedDRA), **Confluence 연구노트 자동화**, **Tailscale 기반 원격 인프라 구성** 등 기획·자동화 작업을 병행합니다.

---

## 🎯 Current Focus

- **On-Premise / 폐쇄망 LLM 서비스** — RAG, 서빙, 오프라인 패키징·배포
- **On-Device AI** — Gemma 4 + LiteRT, 저사양 기기 안정 추론
- **Agentic Development** — Claude Code 멀티에이전트 워크플로, 자동 코드리뷰
- **AI 데이터 파이프라인** — 수집 → 정제 → 데이터셋 생성 → LLM 평가

---

## 📊 GitHub Stats

<p align="center">
<img src="https://streak-stats.demolab.com?user=jangsejong&theme=tokyonight&hide_border=true" height="170" alt="GitHub Streak"/>
</p>

<p align="center">
<img src="https://ghchart.rshah.org/409ba5/jangsejong" width="90%" alt="Contribution Graph"/>
</p>

---

## 📫 Contact

GitHub : https://github.com/jangsejong<br>
Email : sjjang@synergion.com<br>
Phone : 010-8931-이육구일

---

<div align="center">

⭐ **Building the future with AI & Data**

</div>

<!--
Changelog
### v2.0.0 (2026-07-13)
- 프로필 전면 개편: 2026 프로젝트 포트폴리오 반영 (RAG/온디바이스/SaaS/보안/데이터 파이프라인)
- 깨진 GitHub Stats 카드(YOUR_VERCEL_DOMAIN 플레이스홀더) → ghchart + streak-stats로 교체
- Tech Stack 배지 실사용 스택 기준 갱신 (Ollama/Gemma/FastAPI/Next.js/Flutter/Qdrant/k3s)
-->
