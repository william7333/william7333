<!-- =======================
     GitHub Profile README
     william7333
     ======================= -->

<h1 align="center">Hi, I'm Taeho 👋</h1>
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
**Hybrid Retrieval + Recommendation Chatbot** powered by **Elasticsearch(Vector+Keyword)** + **Neo4j(Graph)**  
Also includes **Fake-listing risk evaluation** and **Price evaluation model**.

- ✅ **Retrieval**: BM25 + Vector hybrid search (Elasticsearch), graph-aware filtering (Neo4j)
- ✅ **Recommendation**: user intent → dynamic query/filter generation → ranked candidates
- ✅ **Models**: 허위매물 평가 / 가격평가 결과를 서비스 기능으로 연결
- ✅ **Focus**: 검색 품질(정확도) + 추천 설명가능성 + 서비스 운영 관점(성능/비용) 고려
- ✅ **Stack**: Python · PostgreSQL(pgvector) · Elasticsearch · Neo4j · Docker · AWS
- 🔗 Repo: https://github.com/william7333/GOZIP

---

### 🧠 MentalCounseling_RAG — Multi-Turn Counseling & Mental Health Info Chatbot
**PostgreSQL(pgvector)** 기반 유사도 검색 + **멀티턴 메모리/대화 상태**를 결합한 상담형 RAG.

- ✅ **Vector Search**: pgvector similarity search + metadata filtering
- ✅ **Multi-turn**: conversation context 유지, intent 변화 대응
- ✅ **Safety**: 답변 범위/근거 제시, 오답/환각 억제 프롬프트 설계
- ✅ **Stack**: Python · PostgreSQL(pgvector) · Docker
- 🔗 Repo: https://github.com/william7333/MentalCounseling_RAG

---

### 🌊 Toyroject_WatetSportsRecommendation — Water Sports Spot & Date Recommender
수상레저 추천 **지역+날짜 챗봇**: 사용자 조건과 환경 데이터를 바탕으로 추천 결과 제공.

- ✅ **Recommendation**: user constraints → ranking logic → explanation
- ✅ **Data**: 날씨/해양 지표 기반 추천 시나리오 설계
- ✅ **Stack**: Python · (Backend) FastAPI · (Frontend) React · Docker
- 🔗 Repo: https://github.com/william7333/Toyroject_WatetSportsRecommendation

---

### 🏦 BankQA_RAG — Loan/Deposit Q&A RAG Service (Woori + KB)
은행 **대출/예적금 약관** 기반 Q&A: 문서 근거 중심 답변 + 출처 제시.

- ✅ **RAG**: chunking → embedding → retrieval → grounded answer
- ✅ **Explainability**: 근거 문단/출처 제시, 질문 의도 분류
- ✅ **Stack**: Python · RAG · Docker
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
