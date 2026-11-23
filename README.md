# 멍냥 골프장

강아지·고양이 골퍼로 단풍 든 18홀을 도는 브라우저 3D 골프 게임이에요.
설치 없이 휴대폰·PC 브라우저에서 바로 칠 수 있어요.

- 강아지·고양이 중 골라서 플레이 (이동할 땐 네발로 걷고, 공 앞에선 일어서서 스윙)
- 18홀, 클럽 15종, 바람·경사·벙커·연못
- 그늘집에서 음식·음료 주문
- AI 동반자 감자·당근과 함께 라운드, 스코어카드

## GitHub Pages로 올리는 방법

1. GitHub에서 **New repository** → 이름 예: `mungnyang-golf` → **Public** 으로 만들기
2. 저장소 화면에서 **Add file → Upload files** → 이 폴더 안의 파일과 폴더를 **전부** 끌어다 놓고 **Commit changes**
   - `index.html`이 저장소 맨 위(루트)에 있어야 해요. 폴더째 한 단계 더 들어가 있으면 안 돼요.
   - `.nojekyll`은 숨김 파일이라 안 보일 수 있어요. 없어도 게임은 돌아가요.
3. **Settings → Pages** → Source를 **Deploy from a branch**, Branch를 **main / (root)** 로 고르고 **Save**
4. 1~2분 뒤 같은 화면 위쪽에 주소가 떠요: `https://(내 아이디).github.io/mungnyang-golf/`

주소에 내 아이디가 안 들어가게 하고 싶으면, GitHub에서 **Organization**(무료)을 하나 만들고
(예: `mungnyang-golf`) 그 안에 저장소 이름을 `mungnyang-golf.github.io`로 만들면
`https://mungnyang-golf.github.io/` 로 열려요.

### 방문자 수 보기 (선택)

1. [goatcounter.com](https://www.goatcounter.com)에서 가입, Code에 영문 이름(예: `mungnyang`) 입력
2. Settings에서 **Allow adding visitor counts on your website** 켜기
3. 저장소의 `config.js`를 열어 연필(편집) 버튼 → `goatcounter: ""` 를 `goatcounter: "mungnyang"` 으로 바꿔 Commit
4. 게임 화면 위쪽에 '누적 방문 N회'가 떠요 (반영까지 최대 4시간)

GoatCounter는 쿠키를 쓰지 않고 개인을 식별하지 않는 방문 통계예요.

### 게임을 고친 뒤

바뀐 파일을 같은 방법(Add file → Upload files)으로 다시 올리면 덮어써지고, 1~2분 뒤 사이트에 반영돼요.

## 참고

- 같은 코스에서 다른 사람이 보이는 기능은 claude.ai 안에서만 동작해요. 이 버전은 혼자 + AI 동반자와 쳐요.
- 저장한 기록은 각자 브라우저에만 남아요.
- 사용한 외부 자료와 라이선스는 [CREDITS.md](CREDITS.md)에 있어요.
