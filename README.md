# Mini-AIFFELTHon
Mini-AIFFELTHon??
  - AIFFEL 과정중 진행한 작은 프로젝트를 지칭함
  - 총 6일간 진행(24.11.14~24.11.19)

# 칼로리 췍(CalorieCheck)
  - 건강 관리를 위한 식품 정보 파악 서비스
  - 가공식품의 이미지를 모델이 인식해
    - 가공식품 이름
    - 가공식품의 설명
    - 가공식품의 영양성분을 확인 가능

## 프로젝트 개발 배경
현대 사회에서 건강 관리는 필수적인 요소로 자리 잡고 있으며, 이를 위해 식품 정보를 올바르게 파악하는 것이 중요함. 건강과 가장 밀접하게 연관된 요소는 식습관이며, 이에 따라 다양한 건강 관련 요인들이 영향을 받음.

예를 들어, 알레르기, 당뇨 등의 요소는 식습관과 깊이 관련이 있으며, 식습관이 잘못 관리될 경우 만성질환, 병거로움(질병 발생 위험), 제한(음식 섭취 제한) 등의 문제로 이어질 수 있음.

따라서 식품 정보 파악을 보다 쉽게 영양 정보를 확인할 수 있도록 본 프로젝트를 기획하게 됨.

## 프로젝트 목표
- 식품 정보를 분석하여 자신에게 적합한 식품인지 판단하는 것

## 📚 기술 스택

- LLM & AI
  - PyTorch+YOLOv7
  - Ollama+EEVE
  - Prompt Engineering
  - RAG
  - LangChain
- Front-end
  - Html
  - CSS
  - JavaScript
- Back-end
  - Python
  - Sqlite3
  - Fast-API

## 프로젝트 flowchart
![image](https://github.com/user-attachments/assets/d6d3957f-f38c-481d-853e-0f2d1ca93f14)


## 프로젝트 기여
  - 영양성분 확인에 필요한 DB 생성
  - LLM 모델 선정 및 검색 기반 RAG 구현
  - Fast API를 활용한 웹 제작
  - 최종 프로토타입 실행 프로세스에 기여

## CalorieCheck(프로토타입) 시연

![그림5](https://github.com/user-attachments/assets/a6ed5a32-2ab2-41e9-9ff8-899002bfdf7b)

---

![image](https://github.com/user-attachments/assets/e0f5e915-6105-4c8d-9604-310619ae58dc)

## 프로젝트 결과/성과
- 해당하는 식품의 리뷰, 영양 성분이 잘 도출됨

## 시사점 및 한계
- 식품 정보 파악의 자동화 달성
  - 영양성분과 리뷰가 잘 도출되어 사용자들이 쉽게 정보 확인 가능
- 한계점으로는 음료 제품군에만 적용됨

## 프로젝트를 통해 배운 점과 아쉬운 점이나 보완할 점
- LLM을 Ollama를 통한 local LLM으로 사용 가능하다는 것을 알게 됨
- RAG를 처음 적용해 봤기에 retrieval 기반이 아닌 검색 기반이라 아쉬움
- 음료 제품군뿐만 아니라 다양한 제품군으로 넓혀가야 함
