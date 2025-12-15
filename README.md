# simonyost.com

Static landing page hosted on GitHub Pages.

## Deploy
1. Push to GitHub (repo name can be `simonyost.com`).
2. Settings → Pages → Build and deployment:
   - Source: Deploy from a branch
   - Branch: `main` / root
3. Add custom domain: `simonyost.com`
4. Ensure `CNAME` file exists with `simonyost.com`

## DNS
Create:
- `A` records for `@` → 185.199.108.153 / 109.153 / 110.153 / 111.153
- `CNAME` for `www` → `<your-github-username>.github.io`
Enable “Enforce HTTPS” after DNS propagates.
