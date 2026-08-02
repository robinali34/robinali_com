# robinali.com (static / Jekyll)

Personal site for **[www.robinali.com](https://www.robinali.com/)**, migrated from WordPress to a Jekyll site for GitHub Pages.

- Home design follows the current robinali.com layout (hero, feature cards, nav).
- `/blogs/` lists personal posts migrated from WordPress on robinali.com.
- `/topics/` is the topic-focused blog hub from [robinali34.github.io](https://robinali34.github.io/).

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000/

## GitHub Pages + custom domain

1. Create a **public** repo named `robinali_com` under `robinali34`.
2. Push `main`, then enable **Settings → Pages → Build and deployment → GitHub Actions**.
3. Keep the `CNAME` file (`www.robinali.com`).
4. At your DNS provider, point the domain at GitHub Pages:

| Type | Name | Value |
|------|------|--------|
| `A` | `@` | `185.199.108.153` |
| `A` | `@` | `185.199.109.153` |
| `A` | `@` | `185.199.110.153` |
| `A` | `@` | `185.199.111.153` |
| `CNAME` | `www` | `robinali34.github.io` |

5. In the repo Pages settings, set custom domain to `www.robinali.com` and enable HTTPS once DNS propagates.

Until DNS is switched, the site is also available at `https://robinali34.github.io/robinali_com/` (set `baseurl: "/robinali_com"` temporarily if you need that path to work before the custom domain is live).

## Structure

```
├── index.html          # Home
├── blogs/              # Personal blog index (WordPress posts)
├── _posts/             # Migrated blog posts
├── topics/             # Topic-focused blogs hub
├── assets/             # CSS, JS, images, icons
├── _layouts/           # Jekyll layouts
├── _includes/          # Header / footer
├── CNAME               # www.robinali.com
└── .github/workflows/  # Pages deploy
```
