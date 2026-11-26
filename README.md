<!-- =======================
     GitHub Profile README
     william7333
     ======================= -->

<h1 align="center">AI 엔지니어</h1>
<p align="center">
  <b>DevOps × AI Engineer</b> · Full-Stack Web Developer (RAG) · Search & Recommendation Systems
</p>
<p align="center">
  Python 중심으로 <b>RAG(검색+추천)</b> 시스템을 만들고, <b>PostgreSQL(pgvector)</b> · <b>Elasticsearch(키워드+벡터)</b> · <b>Neo4j(그래프DB)</b>를 조합한 하이브리드 검색/추천 아키텍처에 흥미와 개발 경험이 있습니다.
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

## 📌 What I’m focusing on 
- 🔎 **Hybrid Retrieval Quality**: BM25 + Vector + Graph 기반 랭킹 개선 / 평가 지표 구축
- ⚡ **Latency & Cost**: caching / chunking / embedding 전략 최적화
- 🧱 **Production Architecture**: Dockerized services, observability, CI/CD, safe prompting
---

<!-- Tips:
1) Replace contact placeholders
2) Pin repos: GOZIP, MentalCounseling_RAG, BankQA_RAG, ToyProject...
3) Add 1 screenshot/GIF per project if possible -->
