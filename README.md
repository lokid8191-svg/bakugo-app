# 바쿠고와 일본어 · 실행용 앱

claude.ai에 있는 바쿠고 앱을 폰의 앱 서랍에서 바로 열기 위한 실행용 앱이에요.
앱 아이콘을 누르면 claude.ai의 바쿠고 앱으로 바로 넘어가요. API는 필요 없어요.

## 아이콘 바꾸기 (파일 하나만)

1. 원하는 이미지를 휴대폰 갤러리에서 **자르기 → 1:1(정사각형)**으로 잘라요. 얼굴이 가운데 오게, 가장자리는 조금 여유 있게.
2. 파일 이름을 **icon.png** 로 바꿔요.
3. GitHub 저장소에서 **Add file → Upload files**로 올리면 기존 icon.png를 덮어써요.
4. 이미 설치했다면 앱을 지우고 다시 설치해야 새 아이콘이 보여요.

## 처음 올리는 방법 (GitHub Pages)

1. GitHub에서 새 저장소를 만들어요. 예: `bakugo-app` (Public)
2. 이 폴더의 파일 5개를 올려요: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.png`, `README.md`
3. **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main / (root)** → Save
4. 1~2분 뒤 `https://내아이디.github.io/bakugo-app/` 주소가 생겨요.

## 폰에 설치하기

- **안드로이드 (Chrome)**: 주소를 열고 **앱으로 설치하기**. 버튼이 없으면 ⋮ 메뉴 → **앱 설치**.
- **아이폰 (Safari)**: 공유 버튼 → **홈 화면에 추가**.

## 알아 둘 점

- 그 브라우저에서 claude.ai에 로그인되어 있어야 해요.
- 화면 위에 작은 주소 표시줄이 보일 수 있어요.
- 바쿠고 앱 주소가 바뀌면 `index.html`의 `APP_URL` 한 줄만 고치면 돼요.
