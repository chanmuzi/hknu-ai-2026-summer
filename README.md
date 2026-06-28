# 한경국립대 2026 여름특강 · 딥러닝/머신러닝 입문 (초급반)

비전공자·초급자를 위한 AI 입문 실습 자료입니다.
설치 없이 **Google Colab**에서 바로 실행합니다.

## 빠른 시작
1. 아래 차시 노트북의 **Open in Colab** 배지를 클릭합니다.
2. Google 계정으로 로그인합니다.
3. 코드 셀을 선택하고 **▶ (Shift + Enter)** 로 실행합니다.

> 처음이라면 먼저 [SETUP.md](SETUP.md) 의 환경 준비 가이드를 따라오세요.

## 차시별 실습

### 1차시 · AI 개요와 실습 환경
- Colab 시작하기 (환경 온보딩) — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-1-ai-intro/s1-01-Colab-시작하기.ipynb)

### 2차시 · 머신러닝·딥러닝의 이해와 체험
- 허깅페이스 모델 체험 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-2-ml-dl-basics/s2-01-허깅페이스-모델체험-실습.ipynb)

> OpenAI API 키가 **필요 없습니다.** 사전학습된 공개 모델을 그대로 불러와 체험합니다.
> 일부 모델은 **GPU 권장** — 상단 **런타임 → 런타임 유형 변경 → GPU** 를 켜면 빠릅니다.

### 3차시 · 파이썬과 수학 기초
- 파이썬 ① 변수와 자료형 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-3-python-math/s3-01-파이썬-변수와자료-실습.ipynb)
- 파이썬 ② 흐름과 함수 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-3-python-math/s3-02-파이썬-흐름과함수-실습.ipynb)
- 파이썬 ③ 데이터 다루기 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-3-python-math/s3-03-파이썬-데이터다루기-실습.ipynb)
- 벡터와 행렬 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-3-python-math/s3-04-벡터와행렬-실습.ipynb)

### 4차시 · 데이터 분석과 머신러닝
- Numpy · Pandas · 시각화 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-4-data-analysis/s4-01-넘파이판다스시각화-실습.ipynb)
- Netflix 데이터 분석 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-4-data-analysis/s4-02-Netflix데이터분석-실습.ipynb)
- 머신러닝 분류 (붓꽃) — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-4-data-analysis/s4-03-머신러닝분류(붓꽃)-실습.ipynb)
- 집값 예측 (회귀) — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-4-data-analysis/s4-04-집값예측(회귀)-실습.ipynb)

> **Netflix 분석**은 `session-4-data-analysis/data/netflix_titles.csv` 를 사용합니다. 노트북이 저장소를 `git clone` 해 자동으로 불러옵니다.
> **집값 예측**은 Kaggle *House Prices* 데이터(`train.csv`·`test.csv`)가 필요합니다 — 노트북 안내대로 [대회 페이지](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)에서 내려받아 Colab 파일 패널에 업로드하세요.

### 5차시 · 딥러닝과 RAG 챗봇
- 프롬프트와 챗봇 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-5-prompt-rag/s5-01-프롬프트와챗봇-실습.ipynb)
- RAG 챗봇 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-5-prompt-rag/s5-02-RAG챗봇-실습.ipynb)
- BERT 분류 · 라벨링과 파인튜닝 — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-5-prompt-rag/s5-03-BERT분류-라벨링과파인튜닝-실습.ipynb)
- 멀티에이전트와 NotebookLM — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chanmuzi/hknu-ai-2026-summer/blob/main/session-5-prompt-rag/s5-04-멀티에이전트와NotebookLM-실습.ipynb)

> **프롬프트·RAG·멀티에이전트**(s5-01·02·04)는 **OpenAI API 키**가 필요합니다 — 노트북 실행 중 입력 창에 붙여 넣습니다.
> **BERT 파인튜닝**(s5-03)은 API 키 없이 동작하지만 **GPU 권장** — 학습 속도를 위해 런타임을 GPU 로 바꾸세요.

## 환경
대부분의 패키지는 Colab에 기본 설치돼 있고, 노트북마다 필요한 패키지를 셀에서 직접 설치합니다.
로컬에서 실행한다면 `requirements.txt`를 참고하세요.

```bash
pip install -r requirements.txt
```
