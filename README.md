# Yonghyun Dev 블로그

Astro 공식 블로그 템플릿으로 시작한 개인 블로그입니다.

## 로컬에서 보기

```sh
nvm use
npm install
npm run dev
```

브라우저에서 `http://localhost:4321`을 엽니다.

## 직접 꾸미기

- 블로그 이름과 소개: `src/consts.ts`
- 색상과 기본 스타일: `src/styles/global.css`
- 글 작성: `src/content/blog/`에 Markdown 또는 MDX 파일 추가
- 화면 구성: `src/pages/`, `src/components/`, `src/layouts/`

현재 `src/content/blog/`의 글은 Astro 템플릿 예시입니다. 본인 글로 바꾸거나 삭제하세요.

## 배포

`main` 브랜치에 push하면 GitHub Actions가 사이트를 빌드하고 배포합니다. GitHub 저장소의 **Settings → Pages → Build and deployment → Source**에서 **GitHub Actions**를 선택하세요.
