# Portfolio (Hugo)

Md Muhasin Ali's portfolio, moved from Google Sites to [Hugo](https://gohugo.io/).

Pages: Home, Education, Skills, Hobbies, Let's Contact (all in `content/`).

## Run locally

```bash
hugo server
```

Open http://localhost:1313

## Edit content

- Text and lists live in the front matter of each file in `content/`.
- Images live in `static/images/`. The ones here were cropped from screenshots, so for best quality replace them with the originals (same file names).
- Optional banner photos: add `hero-home.jpg`, `hero-education.jpg`, `hero-skills.jpg`, `hero-hobbies.jpg`, `hero-contact.jpg` to `static/images/`.

## Before publishing

1. In `content/contact.md`, set your real Facebook, Telegram and email links.

## Deploy to GitHub Pages

1. Create a GitHub repo named `muhasin4739.github.io`.
2. Push this folder to the `main` branch.
3. Settings → Pages → Source → **GitHub Actions**.
4. Your link: `https://muhasin4739.github.io/`
