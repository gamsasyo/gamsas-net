# gamsas.net

studio site for **gamsas** — a studio for small strange tools. cameras first.

static one-pager + F33DBAG product page. deployed on Cloudflare Pages.

## structure

```
index.html      studio landing
f33dbag.html    F33DBAG product page (screenshots + looks)
shots/          app screenshots
```

## deploy

connected to Cloudflare Pages — `git push` to the default branch auto-deploys.

manual deploy:

```
npx wrangler pages deploy . --project-name=gamsas
```
