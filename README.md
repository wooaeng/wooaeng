<div align="center">

# 안녕하세요, 전우영입니다 👋

### AI를 직접 만들어 본 경험으로, AI로 일하는 방식을 바꾸는 서비스 기획자

</div>

<br/>

## 🙋 About

- 🧭 **문제에서 시작합니다**: 사용자가 겪는 불편을 정의하고, 요구사항 → WBS → 화면 설계로 풀어내는 기획을 합니다.
- 🤖 **AI를 직접 만들어 봤습니다**: 데이터 수집부터 RAG 구축, 성능 평가까지 직접 해 봤기 때문에 AI로 무엇이 가능하고 어디가 한계인지 압니다.
- 🚀 **끝까지 갑니다**: 4인 팀 PM으로 기획부터 실서비스 배포까지 8주 만에 완주했습니다.

<br/>

## 📂 Projects

### ✈️ Triver: LLM 기반 초개인화 K-Culture 여행 에이전트
`PM` · 4인 팀 · 2026.02 ~ 03 (8주) · 🔗 [triver-s.com](https://triver-s.com/) · [Repository](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-FINAL-2Team)

**🔍 Problem**
방한 외국인은 여행 하나를 준비하려고 앱을 4개 이상 오가야 하고, 국내 앱은 대부분 다국어를 지원하지 않습니다. 팝업스토어처럼 금방 바뀌는 정보는 찾기가 더 어렵습니다.

**🛠 What I did**
- **PM**: 주제 선정, 요구사항 정의, WBS 수립, 화면 설계를 맡았고 주간 진행률을 관리하며 배포까지 리드했습니다.
- **데이터 전략**: "추천 품질은 데이터 품질에서 나온다"고 보고, 한국관광공사·Visit Seoul 등에서 장소 데이터 약 4,800건을 수집해 정제했습니다. 빠진 설명과 태그는 LLM으로 보강했습니다.
- **운영 자동화**: 팝업스토어·공연처럼 기간이 정해진 정보는 스케줄러로 자동 수집하고, 만료되면 자동으로 정리되게 만들었습니다.
- **사용자 경험**: 랜딩·탐색 화면을 반응형으로 다듬고 4개 국어(한/영/일/중) 전환을 적용했습니다.

**📈 Result**
- 실제 도메인으로 서비스 배포 (GitHub Actions 기반 자동 배포)
- 검색 성능 **Recall 0.84 / MRR 0.81**, LLM-as-a-Judge 기준 답변 품질 **0.9점대**
- 📑 기획 산출물: [기획서 · 요구사항 정의서 · WBS · 화면설계서 등](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-FINAL-2Team/tree/main/산출물)

<br/>

### ⚖️ 노동법 RAG 챗봇: 법령 정보 검색 에이전트
`데이터 & 평가` · 6인 팀(노동법 파트 2인) · 2026.01 · [Repository](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN21-3rd-1TEAM) · [웹 서비스·배포](https://github.com/wooaeng/SKN21-4th-1Team-A)

**🔍 Problem**
일반인이 노동 문제를 겪어도 방대한 법령과 판례 속에서 내 상황에 맞는 조항을 찾기 어렵습니다.

**🛠 What I did**
- **데이터 구축**: 국가법령정보센터의 법령, 판례·행정해석·고용노동부 Q&A를 수집하고 법령 구조에 맞게 나눠서 정리했습니다.
- **문제 해결**: 검색된 조문이 어느 법에 속하는지 모델이 헷갈리는 문제를 발견하고, 조문마다 `[법령명] 제N조` 헤더를 붙여 검색 정확도를 높였습니다.
- **평가 설계**: 평가 질문이 실제 사용자 말투와 달라서 점수를 믿기 어렵다고 판단했고, 구어체 상황 질문으로 평가 데이터셋을 다시 만들었습니다. 이후 버전별(V1~V8) 성능을 비교해 개선 방향을 정했습니다.

**📈 Result**
- 의도 분석 → 검색 → 답변 → 자체 검증으로 이어지는, 근거 조항을 함께 답하는 챗봇 완성
- 후속 프로젝트에서 Django 웹 서비스로 만들어 AWS에 배포

<br/>

## 💡 How I Work

- **좋은 서비스는 좋은 데이터에서 나온다.** AI 기능을 기획할 때 데이터부터 확인합니다.
- **작은 버튼에도 이유가 있다.** 화면을 손으로 먼저 그려 보며, 사용자가 왜 여기서 이걸 누르는지부터 고민합니다.
- **PM은 모든 걸 하는 사람이 아니다.** 팀원의 강점이 드러나도록 역할을 나누고, 서로 보완하며 함께 완주합니다.

<br/>

## 🧰 Tools

**Planning & Design**&nbsp;
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

**AI & Tech**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

<br/>

## 📫 Contact

<!-- 이메일, 포트폴리오(노션) 링크를 추가하세요 -->
