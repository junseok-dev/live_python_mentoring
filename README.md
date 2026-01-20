# live_python_mentoring

# 🦜 LangChain을 활용한 라이브 파이썬 멘토링 (Live Python Mentor)

**AI 기반의 실시간 파이썬 코드 분석 및 심층 로직 과외 서비스**입니다.  
단순한 코드 수정을 넘어, 파이썬 인터프리터의 동작 원리를 한 줄씩 상세히 설명하여 학습자의 논리적 사고 성장을 돕습니다.

---

## 🌟 주요 기능 (Key Features)

### 1. 실시간 스트리밍 분석 (Real-time Streaming)
- AI 멘토가 분석 내용을 생성하는 즉시 화면에 한 글자씩 렌더링되어 실제 대화하는 듯한 생동감 있는 경험을 제공합니다.

### 2. 라인별 심층 로직 해설 (Deep Dive Analysis)
- 모든 코드 라인을 분자 단위로 분해하여 설명합니다.
- **데이터 타입 체킹**, **메모리 변화**, **연산 원리**를 상세한 단락 단위로 제공합니다.

### 3. 비주얼 변수 추적 테이블 (Visual Tracer)
- 실행 단계별로 변수의 값과 콘솔 출력(`stdout`)이 어떻게 변하는지 표 형식으로 시각화하여 로직의 흐름을 한눈에 파악하게 합니다.



### 4. 사용자 맞춤형 설정
- **🌓 테마 전환:** 다크(Dark) 모드와 라이트(Light) 모드 중 선택 가능.
- **📏 글꼴 크기 조절:** 사용자의 가독성에 맞춰 12px~30px까지 실시간 조절 가능.
- **🔑 API Key 직접 입력:** 보안을 위해 개별 OpenAI API Key를 입력하여 독립적인 환경 제공.

### 5. 학습 로그 및 히스토리
- 사이드바를 통해 과거의 분석 기록을 저장하고 언제든지 다시 복습할 수 있는 히스토리 기능을 제공합니다.

---

## 🛠 기술 스택 (Tech Stack)

* **Language:** Python 3.10+
* **Frontend:** Streamlit
* **AI Orchestration:** LangChain (v0.3+)
* **LLM:** OpenAI GPT-4o-mini



---

## 🚀 시작하기 (Getting Started)

### 1. 필수 라이브러리 설치
터미널에서 아래 명령어를 실행하여 필요한 패키지를 설치하세요.
```bash
pip install streamlit openai python-dotenv langchain langchain-openai langchain-core
2. 애플리케이션 실행
Bash

streamlit run app.py
📖 사용 방법 (Usage)
API 키 설정: 사이드바 상단에 본인의 OpenAI API Key를 입력합니다.

코드 입력: 왼쪽 에디터에 분석하고 싶은 파이썬 코드를 작성합니다.

디자인 설정: 본인에게 편안한 테마와 글꼴 크기를 선택합니다.

분석 시작: 🚀 실시간 심층 분석 시작 버튼을 클릭합니다.

결과 확인: 오른쪽 리포트에서 실시간으로 생성되는 상세 분석과 시각화 테이블을 확인합니다.

📂 프로젝트 파일 구조
Plaintext

.
├── app.py              # 메인 애플리케이션 코드
├── requirements.txt    # 의존성 패키지 목록
├── .gitignore          # Git 추적 제외 설정
└── README.md           # 프로젝트 안내 문서 (본 파일)
📝 라이선스 (License)
본 프로젝트는 MIT License를 따릅니다. 자유롭게 수정하고 배포하실 수 있습니다.

© 2026 Live Python Mentor - Powered by LangChain & OpenAI


---

### 💡 활용 팁
1. **GitHub 업로드:** GitHub 저장소 메인 페이지에서 `Add file` -> `Create new file`을 누르고 파일명을 `README.md`로 입력한 뒤 위 내용을 붙여넣으세요.
2. **이미지 추가:** 위 내용 중 `` 부분은 실제 앱의 실행 화면을 캡처하여 이미지를 업로드한 뒤 해당 링크로 교체하시면 훨씬 전문적인 문서가 됩니다.
