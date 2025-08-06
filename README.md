# MS_AI_Study

# Day1 2025.08.06
## Env spec
  - IDE : vscode
  - 언어 : python
  - 가상환경 툴 : uv
## uv 사용법
  - uv 프로젝트 초기화 : ```uv init ktds-llm --python=3.12```
    - 폴더명 : ktds-llm
    - 해당 폴더 이동 후 ```code .``` 명령어로 vscode로 실행
  - 가상환경 활성화 : ```uv venv``` -> ```.venv\Scripts\activate``` [복붙 후 엔터]
  - .python-version : uv로 세팅한 파이썬 버전
  - ```where python``` <- 파이썬 위치 확인
## uv 패키지 설치
  - ```uv add langchain langchain_openai python-dotenv ipykernel```
## 작업 수행
  1. .env 파일 생성
    - .env 파일 내, OPENAI_API_KEY=your_api_key_here 작성
     
