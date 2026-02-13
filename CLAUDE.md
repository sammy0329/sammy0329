# sammy0329 — GitHub Profile README

GitHub 프로필 페이지(github.com/sammy0329)에 표시되는 README 리포지토리입니다.

## 파일 구조

```
README.md                         # 메인 프로필 (GitHub 프로필 페이지에 렌더링)
CLAUDE.md                         # 이 파일 — 리포지토리 가이드
github-metrics.svg                # GitHub Actions가 자동 생성 (직접 수정 금지)
.github/workflows/metrics.yml     # Metrics SVG 자동 생성 워크플로우
```

## README 섹션 순서

순서를 변경하지 마세요:

1. **Header** — Typing SVG 애니메이션 + 이름
2. **Contact** — Gmail / Velog / LinkedIn 배지
3. **About Me** — 자기소개
4. **Tech Stack** — 기술 스택 배지 (중앙 정렬)
5. **Projects** — 프로젝트 3개
6. **How I Work with AI** — AI 워크플로우 설명
7. **GitHub Stats** — Stats + Streak 카드
8. **GitHub Metrics** — 자동 생성 SVG
9. **Footer** — 방문자 카운터

## 배지 스타일 컨벤션

- **Tech Stack 섹션:** `for-the-badge` 스타일 (큰 배지)
- **Project 인라인 배지:** `flat-square` 스타일 (작은 배지)
- **Contact 배지:** `flat-square` 스타일

## 프로젝트 추가 포맷

새 프로젝트 추가 시 아래 포맷을 따르세요:

```markdown
### 프로젝트 이름

> 한 줄 설명

**기간:** YYYY.MM.DD ~ YYYY.MM.DD (N일) · **역할:** 역할명

![Tech](https://img.shields.io/badge/기술명-색상?style=flat-square&logo=로고&logoColor=white)

- 성과 1
- 성과 2

[Repository](URL) · [Portfolio](URL)

---
```

## Metrics 워크플로우

- **실행 주기:** 매일 01:00 UTC (10:00 KST)
- **트리거:** schedule / workflow_dispatch / push to main
- **출력:** `github-metrics.svg` (루트에 자동 커밋)
- **필요 시크릿:** `METRICS_TOKEN` (GitHub PAT, `repo` + `read:user` 스코프)
- `github-metrics.svg`는 워크플로우가 생성하므로 직접 수정하지 마세요

## 편집 규칙

- `github-metrics.svg`를 직접 편집하지 마세요
- 배지 색상은 각 기술의 공식 브랜드 컬러를 사용하세요
- Stats 카드 테마는 `tokyonight`으로 통일합니다
- LinkedIn URL은 실제 프로필이 생기면 업데이트하세요
