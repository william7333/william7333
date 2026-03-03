<!-- =======================
     GitHub Profile README
     william7333
     ======================= -->

<h1 align="center">[기술 블로그](https://william7333.github.io.git) </h1>
<p align="center">
  <b>DevOps × AI Engineer</b> · Full-Stack Web Developer (RAG) · Search & Recommendation Systems
</p>
<p align="center">
  Python 중심으로 <b>RAG(검색+추천)</b> 시스템을 만들고, <b>PostgreSQL(pgvector)</b> · <b>Elasticsearch(키워드+벡터)</b> · <b>Neo4j(그래프DB)</b>를 조합한 하이브리드 검색/추천 아키텍처에 큰 흥미와 실전 개발 경험이 있습니다.
</p>

<p align="center">
  <a href="https://github.com/william7333">
    <img src="https://komarev.com/ghpvc/?username=william7333&style=flat&label=Profile%20views" />
  </a>
  <img src="https://img.shields.io/badge/Focus-RAG%20%26%20Search%20Systems-blue" />
  <img src="https://img.shields.io/badge/Deploy-AWS%20%2B%20Docker-232F3E" />
</p>

---

## 🧭 About Me
- 🔥 Interested in **Hybrid RAG**, **Search/Ranking**, **Personalized Recommendation**
- 🧩 Building **production-ready AI web services** (Frontend + Backend + Retrieval + Eval)
- ⚙️ Experience with **AWS** and **Docker** for deployment & 운영 환경 고려
- 🗃️ Heavy user of **PostgreSQL(pgvector)** / **Elasticsearch** / **Neo4j** for retrieval pipelines

---

## 🛠 Tech Stack

### Core (Icons)
<p align="left">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,ts,js,react,nextjs,html,css&perline=11" />
</p>
<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,elasticsearch&perline=11" />
</p>
<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,docker,nginx,linux,git,github,githubactions&perline=11" />
</p>

### AI / Data / Search
<p align="left">
  <img src="https://img.shields.io/badge/RAG-Search%20%2B%20LLM-%23007ACC?style=flat" />
  <img src="https://img.shields.io/badge/VectorDB-pgvector-%234169E1?style=flat" />
  <img src="https://img.shields.io/badge/HybridSearch-Elasticsearch%20(BM25%20%2B%20Vector)-%23005571?style=flat" />
  <img src="https://img.shields.io/badge/GraphDB-Neo4j-%2300A3A3?style=flat" />
  <img src="https://img.shields.io/badge/LLM-OpenAI%20API-black?style=flat" />
  <img src="https://img.shields.io/badge/Orchestration-LangGraph%20%2F%20LangChain-%235A67D8?style=flat" />
</p>

---

## 🚀 Featured Projects

### 🏠 GOZIP — Hybrid RAG Real-Estate Recommendation Platform
Elasticsearch(키워드+벡터)와 Neo4j(그래프DB)를 함께 활용해 “검색 + 추천”이 자연스럽게 이어지도록 설계한 부동산 매물 추천 서비스입니다.  
허위매물 평가 모델과 가격평가 모델 결과를 추천 흐름에 연결해, 단순 추천이 아니라 신뢰도/가격 판단까지 함께 제공하는 것을 목표로 했습니다.

- ✅ Retrieval: BM25 + Vector hybrid search(Elasticsearch) + graph-aware filtering(Neo4j)
- ✅ Recommendation: user intent → dynamic query/filter generation → ranked candidates
- ✅ Models: 허위매물 평가 / 가격평가 결과를 서비스 기능으로 연결
- ✅ Stack: Python · PostgreSQL(pgvector) · Elasticsearch · Neo4j · Docker · AWS
- 🔗 Repo: https://github.com/william7333/GOZIP

---

### 🧠 MentalCounseling_RAG — Multi-Turn Counseling & Mental Health Info Chatbot
PostgreSQL(pgvector) 기반 벡터 검색으로 상담/정신질환 정보를 근거 중심으로 제공하는 멀티턴 RAG 챗봇입니다.  
대화 맥락을 유지하면서 질문 의도 변화에 대응하고, 답변 범위/근거 제시를 통해 안전한 응답을 만들기 위한 프롬프트/흐름을 설계했습니다.

- ✅ Vector Search: pgvector similarity search + metadata filtering
- ✅ Multi-turn: conversation context 유지, intent 변화 대응
- ✅ Safety: 근거 제시, 오답/환각 억제 프롬프트 설계
- ✅ Stack: Python · PostgreSQL(pgvector) · Docker
- 🔗 Repo: https://github.com/william7333/MentalCounseling_RAG

---

### 🌊 Toyroject_WatetSportsRecommendation — Water Sports Spot & Date Recommender
사용자가 원하는 날짜/지역/조건을 입력하면, 환경 지표를 함께 고려해 수상레저에 적합한 장소와 시점을 추천하는 챗봇 프로젝트입니다.  
추천 결과를 단순 나열하지 않고, 왜 그 장소/날짜가 좋은지 설명 가능한 형태로 보여주는 흐름에 집중했습니다.

- ✅ Recommendation: user constraints → ranking logic → explanation
- ✅ Data: 날씨/해양 지표 기반 추천 시나리오 설계
- ✅ Stack: Python · (Backend) FastAPI · (Frontend) React · Docker
- 🔗 Repo: https://github.com/william7333/Toyroject_WatetSportsRecommendation

---

### 🏦 BankQA_RAG — Loan/Deposit Q&A RAG Service (Woori + KB)
우리은행·국민은행의 대출/예적금 약관 문서를 기반으로 질문에 답하고, 근거 문단을 함께 제시하는 금융 Q&A RAG 서비스입니다.  
문서 chunking → embedding → retrieval → grounded answer 흐름을 구성하고, 질문 의도에 맞게 답변 형식과 출처를 정리해 신뢰도를 높이도록 설계했습니다.

- ✅ RAG: chunking → embedding → retrieval → grounded answer
- ✅ Explainability: 근거 문단/출처 제시, 질문 의도 분류
- ✅ Stack: Python · RAG · Docker
- 🔗 Repo: https://github.com/william7333/BankQA_RAG

---

## 📌 What I’m focusing on (2026)
- 🔎 **Hybrid Retrieval Quality**: BM25 + Vector + Graph 기반 랭킹 개선 / 평가 지표 구축
- ⚡ **Latency & Cost**: caching / chunking / embedding 전략 최적화
- 🧱 **Production Architecture**: Dockerized services, observability, CI/CD, safe prompting

---

## 📈 GitHub Stats
<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=william7333&show_icons=true&hide_title=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=william7333&layout=compact" />
</p>

---

<!-- Tips:
1) Replace contact placeholders
2) Pin repos: GOZIP, MentalCounseling_RAG, BankQA_RAG, ToyProject...
3) Add 1 screenshot/GIF per project if possible -->
