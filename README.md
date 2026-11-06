# 노션보이 (@notionboy_) 소개 페이지

노션으로 일상을 정리하는 귀여운 소년, 노션보이의 한 장짜리 소개 페이지예요.
`index.html` 하나에 CSS·JS가 모두 들어 있고 외부 라이브러리나 CDN은 쓰지 않아요.

## 파일 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 사이트 전체 |
| `.nojekyll` | GitHub Pages에서 Jekyll 처리를 건너뛰는 빈 파일 |
| `README.md` | 이 안내문 |

## GitHub Pages 배포

1. GitHub에서 새 저장소를 Public으로 만들어요.
2. **Add file → Upload files**로 세 파일을 올리고 Commit해요.
   - `.nojekyll`은 숨김 파일이라 Mac은 Finder에서 `Cmd + Shift + .`, Windows는 탐색기 **보기 → 숨긴 항목**을 켜야 보여요.
3. **Settings → Pages**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 저장해요.
4. 1~2분 뒤 `https://아이디.github.io/저장소이름/`으로 접속해요.

> 저장소 이름을 `아이디.github.io`로 만들면 `https://아이디.github.io/`로 바로 열려요.
> 커스텀 도메인은 **Settings → Pages → Custom domain**에서 연결할 수 있어요.

## 수정 안내

- **브랜드 컬러**: `index.html` 위쪽 `:root`의 `--blue`(#1959C2), `--gray`(#E9E9E9)
- **링크**: 인스타그램 `https://www.instagram.com/notionboy_/`, 블로그 `https://blog.naver.com/notionboy_`, 협업 문의 `mailto:` 주소
- **캐릭터 이미지 넣기**: 이미지를 `index.html`과 같은 폴더에 올리고, 첫 화면의 `.page-card` 블록을 `<img src="notionboy.png" alt="노션보이">`로 바꾸면 돼요.
- **링크 미리보기 이미지**: 배포 후 `<head>`에 `<meta property="og:image" content="https://아이디.github.io/저장소이름/og.png">`를 추가하면 공유할 때 썸네일이 보여요.

© 2026 노션보이. All rights reserved.
