# LSSC Recruiting Part 채용 이벤트 페이지

`index.html` 한 장으로 만든 정적 페이지입니다. 빌드 과정이 없어서 파일을 더블클릭해서 열어도 그대로 보이고, 어디에 올려도 바로 동작합니다.

## 구성
- `index.html` — 전체 페이지 (Hero, 팀 소개, Recruiting Part 소개, 팀장 한마디, 오픈 포지션 2건, 채용 프로세스, 복리후생, Footer)
- 오픈 포지션의 "지원하기" 버튼은 실제 나인하이어 공고로 새 탭 연결됩니다.
  - Recruiting Part Lead → https://lssc.ninehire.site/job_posting/cYm3qM1f
  - Recruiting Business Partner → https://lssc.ninehire.site/job_posting/pYtOZ9F4

## 배포 방법 (GitHub Desktop + Vercel, CLI 설치 불필요)

### 1) GitHub에 올리기
1. https://desktop.github.com 에서 GitHub Desktop 설치 후 GitHub 계정으로 로그인
2. `File > Add Local Repository` 에서 이 폴더(`lssc-recruiting-event`) 선택
3. 화면에 나오는 `Publish repository` 버튼 클릭 (Private/Public 선택 후 그대로 진행)

### 2) Vercel에 배포하기
1. https://vercel.com 에서 GitHub 계정으로 로그인
2. `Add New... > Project` 클릭 → 방금 올린 `lssc-recruiting-event` 저장소 선택 → `Import`
3. 설정 변경 없이 `Deploy` 클릭 (정적 페이지라 별도 설정 불필요)
4. 배포 완료 후 나오는 주소(예: `lssc-recruiting-event.vercel.app`)를 복사

### 3) 나인하이어 상단 탭 연결
나인하이어(lssc.ninehire.site) 관리자 설정에서 Home 옆에 새 탭을 만들고, 2단계에서 복사한 Vercel 주소를 외부 링크로 연결하면 됩니다.

## 이후 문구 수정이 필요할 때
`index.html` 안의 텍스트를 그대로 찾아 바꾸면 됩니다. GitHub Desktop에서 변경사항을 커밋하고 `Push origin`만 누르면 Vercel이 자동으로 재배포합니다.
