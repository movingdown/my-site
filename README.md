# 이동하 — Developer Portfolio

호기심을 코드로 옮기는 개발자, **이동하**의 자기소개 페이지입니다.
순수 HTML과 CSS, 약간의 바닐라 JS만으로 만들었으며, 외부 라이브러리·빌드 도구 없이 단일 파일로 동작합니다.

## 미리보기

| 섹션 | 내용 |
| --- | --- |
| **Hero** | 인사말, 한 줄 소개, 프로필 이미지, 코드 스니펫 카드 |
| **Portfolio** | StudyPlanner, SmartFileOrganizer, TrendAnalyzer, ExamSurvival 프로젝트 카드 |
| **Hobbies** | 게임, 영화, 음악 등 코드 밖의 시간들 |
| **Contact** | Email, GitHub, Instagram 링크 |

## 구조

```
my-site/
├── index.html   # 페이지 전체 (HTML + CSS + JS 인라인)
└── README.md
```

프로필 사진은 `data:image/jpeg;base64,...` 형태로 HTML 안에 함께 임베드되어 있어,
별도의 이미지 파일 없이 `index.html` 하나만으로 페이지가 완성됩니다.

## 실행 방법

저장소를 클론하거나 파일을 내려받은 뒤, `index.html`을 브라우저에서 열기만 하면 됩니다.

```powershell
# 클론
git clone https://github.com/movingdown/my-site.git
cd my-site

# 브라우저로 열기 (Windows)
start index.html
```

## GitHub Pages로 배포하기

1. GitHub에 새 저장소를 만들고 이 폴더를 push 합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Source**를 `Deploy from a branch`로 설정하고, Branch를 `main` / 폴더는 `/ (root)`로 지정합니다.
4. 잠시 뒤 `https://<username>.github.io/<repo-name>/` 주소에서 페이지가 공개됩니다.

## 사용 기술

- HTML5 (시맨틱 마크업, `aria-*` 속성)
- CSS3 (CSS 변수, Grid, Flexbox, `clamp()`, 미디어 쿼리, `prefers-reduced-motion` 대응)
- Vanilla JavaScript (연도 자동 갱신, 카드 호버 글로우 효과)

## 디자인 메모

- 다크 테마, 보라색 그라데이션(`#8e2de2 → #4a00e0`)을 메인 톤으로 사용했습니다.
- 모노스페이스 폰트(JetBrains Mono / Consolas)를 곳곳에 섞어 개발자스러운 분위기를 살렸습니다.
- 880px / 560px 기준의 반응형 레이아웃을 적용해 모바일에서도 읽기 좋게 동작합니다.

## 연락처

- **Email**: dongha8268@naver.com
- **GitHub**: [@movingdown](https://github.com/movingdown)
- **Instagram**: [@moving_down](https://www.instagram.com/moving_down/)

---

© 이동하 — built with HTML &amp; CSS.
