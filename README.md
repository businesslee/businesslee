# 👋 이정윤 | Jeongyun Lee

> **Data Engineer · Frontend Developer · BI Analyst**  


안녕하세요, 단순히 분석 결과를 내는 것에 그치지 않고
**데이터 흐름 전체(수집 → 적재 → 시각화 → 서비스)** 이해 기반으로 분석하는 데이터 엔지니어 이정윤입니다.

```
📍 Contact.  ✉️ sophia9532@naver.com  🔗 https://github.com/businesslee
```

---

## 🛠 Skills

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

---

## 📌 Certificates

SQLD · ADsP · Azure AI Fundamentals · e-Test OA Master · OPIc IM2

---

## 📂 Projects

### 3. 📱 (Azure 기반) 구매 데이터 기반 리콜 자동 매칭 및 경보 서비스 — Recall, The Safe Check

> **팀명:** Avitor | **역할:** DB/ERD 설계, React Native 프론트엔드 개발 | **기간:** 2026.01.12 ~ 2026.02.27

**[🔗 GitHub Repository](https://github.com/2dt-final-team/Recall-Project)**

#### 💡 문제 정의
> 리콜 발생 시 소비자들이 겪게 되는 Pain Point를 해결하고자
> 리콜이 발생했을 때, Recall 앱을 통해 사용자가 내가 등록한 제품을 기준으로 알람을 받고,
> 실제 조치도 확인할 수 있는 자동 매칭 리콜 경보 시스템 구현

#### 🎯 내 역할 & 핵심 기여

**① Database Engineer / Data Modeler**
- `Azure PostgreSQL Flexible Server` 기반 서비스 DB 설계
- auth·commerce·recall·master 도메인 분리 ERD 설계
- `device_id · push_token · JWT` 연계 인증 세션 구조 협업

**② React Native 프론트엔드 개발**
- 바코드 스캔 → 제품 조회 → 내 물품 등록 핵심 사용자 흐름 구현
- 탭 하이라이트, 로딩 상태, 이미지 잔상 등 UX 개선

**③ Azure 인프라 협업**
- PostgreSQL, Event Hubs, Functions, AI Search 서비스 구성 방향 협의

#### 🧰 사용 기술
`Azure PostgreSQL` `SQL` `React Native` 

#### 📈 결과
- 바코드 스캔 → 리콜 확인까지 실동작 가능한 사용자 시나리오 완성
- 실제 시연 가능한 앱 완성도 확보

---

### 2. 🏭 (Azure 기반) 실시간 예지보전 및 전력 사용량 예측 기반 스케줄링 최적화 시스템 — FacFLEXity

> **팀명:** FacFLEXity | **역할:** 팀장, ML 실험 학습, React 웹 대시보드 개발  | **기간:** 2025.12.10 ~ 2025.12.23

**[🔗 GitHub Repository](https://github.com/2dt-2nd-team/FacFLEXity-web)**

#### 💡 문제 정의
> 스마트팩토리에서 설비 고장(다운타임)과 전력 피크 비용을 동시에 줄이는 통합 체계가 없음  
> 설비 데이터와 에너지 데이터가 분리되어 있어 통합 대응 불가
> 전력 사용량과 현장 설비 상태(예지보전)를 실시간으로 예측·통합하여 "즉시 적용 가능한 의사결정을 보조하는 시스템" 프로젝트 진행

#### 🎯 내 역할 & 핵심 기여

**① 프로젝트 PM (팀장)**
- 주제 정의, 역할 분담, Miro·Notion·GitHub 기반 협업 운영

**② 예지보전 ML 학습 (Databricks)**
- Bronze–Silver–Gold 메달리온 파이프라인 구조 정리
- 센서(AutoML) / 멀티모달(센서+열화상) 모델 실험, 학습 진행 및 비교

**③ React 웹 대시보드 개발**
- `Vite + React + TypeScript` 기반 웹 대시보드 구현
- 폴더 구조·라우팅·페이지/컴포넌트 분리 설계
- 공정 스케줄 타임라인(Line별 상태 표시), 전력량 예측 모니터링, Conveyor 설비 상태 등 화면 구현

#### 🧰 사용 기술
`React` `TypeScript` `Vite` `Databricks` `Azure ML` `Python` `SQL`

#### 📈 결과
- 전력 비용 절감·설비 고장 리스크 감소, 투명한 의사결정 지원
- 팀장 역할로 문제 정의–아키텍처–기능–발표 흐름을 하나의 서비스처럼 연결하는 PM 경험

---

### 3. 🔖 직무/기술 트렌드 기반 도서 추천 플랫폼 — Book Recommendation Platform

> **팀명:** 취취뽀뽀 | **역할:** 팀장, Power BI 시각화 | **기간:** 2025.10.20 ~ 2025.11.19

**[🔗 GitHub Repository](https://github.com/CCPP-1st-team/Book-Recommendation-Platform)**

#### 💡 문제 정의
> 취업 준비생이 "어떤 직무에, 어떤 기술이 필요한지" 채용공고에서 흩어진 정보를 한눈에 볼 수 없었음
> 채용공고 기반 직무 트렌드를 분석해, 신입/전직자에게 맞춤 도서를 추천하는 지식 플랫폼 서비스 구현

#### 🎯 내 역할 & 핵심 기여
- **PM 역할**: 프로젝트 범위 정의, 역할 분담, 협업 체계(Miro·Figma·GitHub) 운영
- **데이터 파이프라인 설계**: 채용공고 데이터 수집 → 직무 키워드 추출 → 도서 매핑 흐름 설계
- **Power BI 시각화**: 직무별 키워드 트렌드 대시보드 시각화 방향 설계 및 구현

#### 🧰 사용 기술
`Azure` `Power BI` `Python` `GitHub` `Figma`

#### 📈 결과
- 직무/기술 트렌드를 기반으로 도서를 추천하는 서비스 컨셉과 시각화 결과물 완성

---

## 📌 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=businesslee&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=businesslee&layout=compact&theme=default&hide_border=true)
