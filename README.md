# 0x Dev Blog

Hugo site. Netlify builds and deploys every push to `main` (config: `netlify.toml`).
The only tool you need locally is [Hugo extended](https://gohugo.io/installation/). No Node or Sass is required.
Run all commands from the repo root.

## Write a post

```sh
hugo new content posts/my-post.md   # creates a draft from archetypes/default.md
hugo server -D                      # preview at http://localhost:1313 (drafts included)
```

Images go in `static/assets/` and are referenced as `/assets/name.png`.

## Publish

Set `draft = false` in the post's front matter, then run:

```sh
git add -A && git commit -m "New post: my post" && git push
```

## Layout

- `content/`: posts and the about page
- `layouts/`: overrides of the vendored `themes/nightfall` templates
- `assets/css/theme.css`: the nightfall theme's SCSS, precompiled to plain CSS
- `assets/css/custom.css`: site-specific styles (edit this one)

When upgrading Hugo, bump `HUGO_VERSION` in `netlify.toml` to match `hugo version`.
