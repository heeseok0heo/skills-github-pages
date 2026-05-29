# Heeseok Heo Portfolio

Hugo 기반 GitHub Pages 포트폴리오 사이트입니다.

## 핵심 구조

- `content/`: 수정 가능한 Markdown 원본
- `static/`: CNAME, 이미지, 데모 앱 같은 정적 파일
- `themes/triple-hyde/`: Hugo 테마
- `.github/workflows/pages.yml`: GitHub Pages 자동 배포

## 로컬 실행

```bash
hugo server -D
```

## 배포

GitHub 저장소의 Pages 설정에서 **Build and deployment > Source = GitHub Actions**를 선택합니다.
`main` 브랜치에 push하면 GitHub Actions가 Hugo를 빌드하여 Pages에 배포합니다.

## 커스텀 도메인

`static/CNAME`에 다음 도메인을 둡니다.

```text
skills.xsim2026.shop
```
