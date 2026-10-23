# WORKLOG · 리아의 여행 블로그 워크플로우

과제 (b)(c)를 쓸 재료. 짧게 적는다.

## 2026-10-23

### 한 일
- 컴퓨터 확인: Windows 11, git 2.55, GitHub CLI(gh) 로그인 됨
- 이 폴더를 git init, `.gitignore`(.env*, .claude/settings.local.json 포함) 만들고 첫 커밋
- 4기 저장소에서 케이 키트 폴더 하나만 sparse checkout(필요한 폴더만 받기)으로 임시 폴더에 받음
  → `kit_원본/` 으로 복사(.git 없이) → 임시 폴더 삭제
- `kit_원본/` 파일을 읽기 전용으로 표시 (실수로 고치지 않게)

- 키트 전체 읽기(README, 스타터킷 HTML, 00~04) → 설치 현황 표 정리
- Aside CLI 설치 시도: 공식 문서(docs.aside.com/help/developers) 윈도우 명령 확인,
  설치 파일 서명(AT YOUR SIDE INC, 유효) 확인 후 실행

### 막힌 곳과 넘은 법
- 키트 받기: 막힘 없음. gh 로그인이 이미 되어 있어서 비공개 저장소도 바로 받아짐
- Aside CLI 설치 실패: Claude 데스크톱 앱 안에서 돌린 설치는 앱 전용 칸(가상화된 폴더)에
  깔려서 `current\aside.exe`를 못 찾고 멈춤 → 반쯤 깔린 것 지우고(PATH는 안 바뀜),
  **리아 님이 Aside 앱의 개발자 설정에서 직접 CLI를 깔기**로 방향 바꿈
- Aside 설치 파일에 SmartScreen(윈도우 낯선 앱 경고)이 뜸 → 다운로드 파일 서명을 검사해
  게시자 AT YOUR SIDE INC·유효 확인 → 「추가 정보 › 실행」으로 설치
- Aside 첫 화면의 크롬 가져오기가 크롬이 켜져 있어 멈춤 → 건너뛰거나 크롬 닫고 다시
- Aside AI 구독은 「Claude」(이미 내는 구독 재사용, 추가 0원) 선택
- 로그인 정리: Aside 계정은 구글로, 네이버는 Aside 브라우저 안에서 따로 (리아가 직접)
- CLI 설치 후 `.mcp.json`(Claude↔Aside 연결 설정)을 이 폴더에 만듦.
  데스크톱 앱엔 `claude` 명령이 없어서 키트의 `claude mcp add` 대신 이 파일로 연결.
  시험: aside mcp 응답 OK, 도구 4개(browser_profiles, repl, memory_search, exec)

### 키트에서 바꾼 것과 이유
- (아직 없음)

### 검사에 걸린 것과 고친 법
- (아직 없음)

### 인터뷰에서 정한 Before → After
- (인터뷰 후 채움)

## 다음에
- 두 번째 후보 키트: 배짱의 Copy OS
