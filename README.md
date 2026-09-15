# soeun4159.github.io

GitHub Pages + Jekyll 기반 개인 보안 블로그입니다.

## 새 글 작성 방법

앞으로는 기존처럼 `posts.html`과 개별 HTML 파일을 둘 다 수정할 필요가 없습니다.

1. `_drafts/new-post-template.md` 파일 내용을 복사합니다.
2. `_posts/년-월-일-영문제목.md` 형식으로 새 파일을 만듭니다.
   - 예: `_posts/2026-09-15-sql-injection.md`
3. 파일 위쪽의 `title`, `date`, `category`, `image`, `excerpt`를 수정합니다.
4. 아래에는 Markdown으로 본문만 작성합니다.
5. 커밋하면 GitHub Pages가 자동으로 게시글 페이지를 생성하고 `posts.html` 목록에도 자동 추가합니다.

## 카테고리 값

- `개발` → `badge_class: dev`
- `CTF/Wargame` → `badge_class: ctf`
- `BugBounty` → `badge_class: bugbounty`
- `블로그/기술문서` → `badge_class: blog`
- `논문/컨퍼런스` → `badge_class: paper`
- `공모전/자격증` → `badge_class: cert`

## 이미지

이미지는 기존처럼 `images/` 폴더에 올리고 Markdown 글의 front matter에 다음처럼 적으면 됩니다.

```yaml
image: "/images/example.jpg"
```

본문 안에서는 다음처럼 사용할 수 있습니다.

```markdown
![설명](/images/example.jpg)
```

## 기존 글

기존 `posts/post1.html` ~ `post8.html` 파일은 그대로 보존합니다. 따라서 기존 URL과 디자인은 깨지지 않습니다. 새 글부터 Jekyll/Markdown 방식으로 작성하면 됩니다.
