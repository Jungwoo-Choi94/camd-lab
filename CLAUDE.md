# CAMD Lab 홈페이지

단국대학교 최정우 교수 연구실 홈페이지.

## 배포

- 사이트: https://jungwoo-choi94.github.io/camd-lab/
- 로컬 파일: `index.html` (단일 파일, CSS·JS 인라인)
- 수정 후 배포: `git add index.html && git commit -m "설명" && git push`

## 색상 팔레트

- `--bg: #f3f4ee` / `--ink: #182e2b` / `--muted: #5b6b65` / `--line: #cbd2c8` / `--accent: #c5f06c`

## 페이지 탭

`showPage(pageId, navHref)` 함수로 전환.

| ID | 내용 |
|---|---|
| page-home | Hero + keywords strip |
| page-research | Approach.png + multiscale-original2.png + 영상 오버레이 |
| page-people | Members 카드 그리드 |
| page-bio-jungwoo | 최정우 교수 상세 bio |
| page-publications | 논문 목록 + 필터 |
| page-gallery | 비어있음 |
| page-news | 비어있음 |

탭 밖(항상 표시): Recruit + Contact 섹션

## Publications 필터

- `data-category="first|co"` + `data-kw="Electrocatalysis,..."` 속성으로 필터링
- Author 필터(All/First/Co)와 Keyword 필터(Electrocatalysis/Thermocatalysis 등)는 독립 작동

## Research 탭 이미지

- 모든 이미지/영상 오버레이에 `mix-blend-mode:multiply` 적용 (흰 배경 제거)
- 컨테이너 배경: `var(--bg)` (흰색 아님)

## Assets 목록 (사용 중)

- `Approach.png`, `Catalyst.png`, `multiscale-original2.png`
- `md-dynamics.gif`, `catalyst-dynamics.mp4`
- `jungwoo-choi.jpeg`
