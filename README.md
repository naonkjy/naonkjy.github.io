# naonkjy.github.io

이 저장소는 GitHub Pages와 Jekyll Chirpy 테마로 운영하는 이유식·유아식 레시피 블로그입니다.

## 로컬 실행

Ruby 3.1 이상 4.0 미만 환경이 필요하며, 이 저장소는 `.ruby-version`으로 `3.4.0`을 지정합니다.

```bash
bundle install
bundle exec jekyll serve
```

기본 실행 주소는 `http://127.0.0.1:4000` 입니다.

## 배포

`main` 브랜치에 push하면 GitHub Actions로 Pages 배포가 진행됩니다.
