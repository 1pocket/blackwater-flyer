# The Brooklyn Blackwater Flyer

A tiny newspaper-that-isn’t: 1920s train schedule × park-ranger bulletin board. Quirky, eccentric, Appalachian.

## Quickstart (Netlify)

1. **Create a GitHub repo** and push this folder.
2. In **Netlify**, click **New site from Git** → connect your repo.
3. **Build settings**: No build command needed. Publish directory: `/` (root).
4. Deploy. That’s it — it’s a fully static site.

> If you later want Markdown posts and archives, you can convert this to Eleventy or Astro. For now, it’s just HTML/CSS so it’s lightning fast and ultra-obscure.

## Customize

- Edit the home page at `index.html`.
- Add posts in `posts/` (copy `first-dispatch.html` as a template).
- Colors & fonts live in `assets/css/style.css`.
- Masthead logo is `assets/img/logo.svg` — editable text inside the SVG.

## Suggested Branch Protection

Since this is a “flyer,” keep `main` clean:
- Use feature branches like `dispatch/2025-10-03` for new posts.
- Open a PR, preview on Netlify, merge to publish.

## License

MIT — see `LICENSE`.