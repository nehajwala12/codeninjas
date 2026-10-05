# Project Black Belt — CreditSwan demo (Code Ninjas)

Static site, no build step. `index.html` is fully self-contained (fonts load from Google Fonts).

## Deploy to Vercel

**CLI (fastest)**
```
cd project-black-belt
npx vercel --prod
```
When prompted: framework preset **Other**, build command **none**, output directory **`.`** (the default).

**Git**
Push this folder to a GitHub repository, then in Vercel choose *Add New → Project*, import the repository, set Framework Preset to **Other**, leave Build Command empty, and deploy.

## Notes
- `vercel.json` sets clean URLs and a `noindex` header so the demo is not indexed by search engines. Remove that header if you want it public.
- Deep links work as `/#pricing` or `/#value/va-bridge`.
- Demonstration edition: exhibits tagged *Illustrative* are synthetic sample data.
