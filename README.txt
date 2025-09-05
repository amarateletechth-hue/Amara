# Amara Teletech — Starter Site

This is a single-file website ready for **GitHub Pages**.

## How to publish (GitHub Pages)
1) Create a free GitHub account and a new repo (any name).
2) Upload `index.html` to the **root** of the repo.
3) In **Settings → Pages**, set:
   - Source: *Deploy from a branch*
   - Branch: `main` (or `master`) — Folder: `/ (root)`
4) After it builds once, add your **custom domain**:
   - Settings → Pages → Custom domain: `amarateletech.co.th`
   - Save and enable **Enforce HTTPS** when it appears.

## DNS records (set at your registrar)
Use these A records for the root (apex) domain:
```
@  185.199.108.153
@  185.199.109.153
@  185.199.110.153
@  185.199.111.153
```
And a CNAME for `www` pointing to your GitHub user site:
```
www  YOUR-USERNAME.github.io
```

> Remove any Wix nameservers. DNS must be managed where you add the above “A” and “CNAME” records.
