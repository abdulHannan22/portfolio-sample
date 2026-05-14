# Sample-portfolio

This is a static portfolio site (single `portfolio.html`).

## Deploy to Vercel

You can deploy this project to Vercel in two ways:

1) Quick (GitHub)
- Push this repo to GitHub (already done).
- Go to https://vercel.com, sign in, and import the GitHub repo.
- Vercel will detect a static project; the site will deploy automatically.

2) CLI (manual)
- Install Vercel CLI:

```bash
npm i -g vercel
```

- From the project root run:

```bash
vercel login
vercel --prod
```

- The first run links the project to your Vercel account. Subsequent commits to the `main` branch will auto-deploy if you used the Git integration.

## Notes
- `vercel.json` is included to serve `portfolio.html` as the site root.
- If you want me to run the `vercel` CLI here, I can attempt it — I'll need you to confirm you have a Vercel account and are okay with me invoking the CLI (it may prompt for login).
