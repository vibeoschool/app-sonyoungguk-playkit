# Playkit

빌드 없이 브라우저에서 바로 열리는 미니 앱 모음입니다. 대부분 별도의 설치나 서버 없이 HTML 파일을 열기만 하면 동작하고, 오프라인에서도 사용할 수 있습니다 (수업지도안 생성기, 공무원연금 계산기, 사이언스로그는 예외로, 별도 저장소에서 관리·배포되는 앱입니다).

## 앱 소개

| 앱 | 설명 |
|---|---|
| ⏱️ **[Focus](focus.html)** | 뽀모도로 집중 타이머와 할 일 목록. 25분 집중 세션을 자동으로 기록합니다. |
| 🎨 **[Kaleido](kaleido.html)** | 마우스 드래그로 그리는 대칭 만화경. 무지개 색과 거울 모드를 지원하고 PNG로 저장할 수 있습니다. |
| 🌈 **[Color Rush](colorrush.html)** | 글자에 칠해진 색을 빠르게 맞히는 반사신경 게임. 스트룹 효과에 도전해 보세요. |
| 🎲 **[Dice](dice.html)** | 상자 안에서 3D 주사위가 굴러다니다 멈추고, 나온 눈의 합을 보여줍니다. 1~5개까지 굴릴 수 있습니다. |
| 🪑 **[Seats](seats.html)** | 학생 명단으로 교실 자리를 랜덤 배정합니다. 제외석·고정석·자리교환, 앞뒤 시점 전환, 배치도 이미지 저장을 지원합니다. |
| 🎡 **[Roulette](roulette.html)** | 인원수만큼 칸이 생기는 번호 뽑기 룰렛입니다. 효과음과 함께 돌다가 멈추고, 뽑힌 번호 제외 모드도 지원합니다. |
| 📝 **[수업지도안 생성기](https://lesson-plan-generator-steel.vercel.app)** | 교과서 PDF와 수업 아이디어를 입력하면 AI가 강의식·토론식·활동중심식 지도안 3안을 생성합니다. Word 다운로드 또는 Google Docs 저장 지원. ([별도 저장소](https://github.com/SonYoungguk/lesson-plan-generator), 인터넷 연결 필요) |
| 💰 **[공무원연금 계산기](https://sonyoungguk.github.io/pension-calculator/)** | 법령 기반으로 공무원 퇴직연금·퇴직수당·실수령액을 추정하고, 언제 퇴직하는 것이 유리한지 시점별로 비교합니다. ([별도 저장소](https://github.com/SonYoungguk/pension-calculator), 인터넷 연결 필요) |
| 🧪 **[사이언스로그](https://science-log.vercel.app)** | 매일 아침 과학·교육 뉴스를 자동으로 모아 과목·학년별로 정리해주는 중학교 과학 교사용 뉴스 로그. 별표로 스크랩도 가능합니다. ([별도 저장소](https://github.com/SonYoungguk/science-log), 비밀번호 필요) |

## 사용 방법

1. 이 저장소를 내려받거나 클론합니다.
   ```
   git clone https://github.com/SonYoungguk/playkit.git
   ```
2. `index.html`을 웹 브라우저로 엽니다.
3. 카드를 클릭하면 각 앱이 열립니다.

서버가 필요 없으므로 파일을 더블클릭해서 바로 열어도 됩니다.

## 기술 스택

대부분 순수 HTML, CSS, JavaScript로만 작성되었습니다. 외부 라이브러리나 빌드 도구를 사용하지 않습니다. (수업지도안 생성기는 Next.js 기반 서버 앱, 공무원연금 계산기는 Vite + React 앱, 사이언스로그는 정적 프론트+Supabase 기반 앱으로 각각 별도 저장소에서 관리됩니다.)
