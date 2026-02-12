# Wisignal Technologies static site

This repository contains a minimal static landing page for Wisignal Technologies Pvt Ltd.

Quick deploy instructions (GitHub Pages with custom domain `wisignal.in`):

1. Create a GitHub repository (e.g. `wisignal.in`) and push these files to the `main` branch:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/wisignal.in.git
git push -u origin main
```

2. In the repository Settings → Pages, set the source to `main` branch (root). GitHub Pages will publish the site.

3. DNS for `wisignal.in` (apex domain): add A records pointing to GitHub Pages IPs:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

If your DNS provider supports ALIAS/ANAME for the apex domain you may use that instead. After DNS changes, GitHub will provision TLS (may take a few minutes).

4. The `CNAME` file included here ensures GitHub Pages knows the site uses `wisignal.in`.

Need help pushing to GitHub or configuring DNS? Reply and I’ll run the commands or guide you step-by-step.
