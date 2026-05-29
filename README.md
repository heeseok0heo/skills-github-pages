# Heeseok Heo GitHub Pages

Hugo 기반 Software Architect 포트폴리오 사이트입니다.

## Information Architecture

- `content/about.md`: 소개 및 학력 배경
- `content/experience.md`: 회사별 경력
- `content/expertise.md`: 핵심 전문 영역
- `content/projects/`: 대표 프로젝트 목록 및 상세 페이지
- `content/technologies/`: 기술 노트 및 세부 항목
- `content/publications.md`: 학위 논문 및 연구 배경

## Deployment

GitHub Pages 설정에서 **Source = GitHub Actions**를 사용합니다.

- Custom domain: `skills.xsim2026.shop`
- CNAME: `static/CNAME`
- Workflow: `.github/workflows/pages.yml`

## Maintenance

HTML 산출물은 직접 수정하지 말고 Markdown 원본을 수정한 뒤 `main` 브랜치에 push합니다.
