# Parente Borean — local site

This folder is the full static website. It does not need WordPress.

## See it on this computer

Open `all-pages.html` or `index.html` in a browser, or run:

```
python -m http.server 8765
```

Then open http://127.0.0.1:8765/all-pages.html

## What is included

- Home, About, Careers, Contact
- 6 practice pages
- 7 lawyer pages
- 8 blog articles
- Logo and firm styles (navy, serif headings)

## New Cloudflare account

Do not put the new email or password in this folder.

1. Sign in at https://dash.cloudflare.com with the new account.
2. Workers & Pages → Create → Pages → Upload assets.
3. Project name: `parenteborean`
4. Upload this folder (the HTML, `styles.css`, and `assets`).
5. After it is live on `*.pages.dev`, add custom domains only when IT can change DNS.

Leave email DNS (MX, SPF, mail, vpn, autodiscover) with IT. This folder is the website only.
