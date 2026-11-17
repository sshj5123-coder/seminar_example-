# Amazon Quick 세미나 신청 페이지

이테크시스템 Amazon Quick 오프라인 세미나(2026.11.19) 신청 페이지입니다.
빌드 과정이 없는 정적 HTML 사이트이며, GitHub `main` 브랜치에 변경이 올라가면 Vercel이 자동으로 배포합니다.

## 구조

| 파일 | 설명 |
| --- | --- |
| `index.html` | 세미나 신청 페이지 (사이트 루트 `/`) |
| `vercel.json` | Vercel 설정 — 확장자 없는 URL, HTML 캐시 즉시 갱신 |

다른 페이지를 추가하려면 같은 폴더에 `파일명.html`을 넣으면 `/파일명` 주소로 열립니다.

## 업데이트 방법

1. 이 폴더의 `index.html`을 수정합니다.
2. GitHub `main` 브랜치에 커밋·푸시합니다. (GitHub Desktop: Commit → Push origin)
3. 1분 내외로 Vercel이 자동 배포하고, 운영 주소에 반영됩니다.

- `main` 외 브랜치에 푸시하면 미리보기(Preview) 주소가 따로 생성되어, 운영 페이지에 반영하기 전에 확인할 수 있습니다.
- 배포 이력과 롤백은 Vercel 대시보드 → 프로젝트 → Deployments에서 확인합니다.
