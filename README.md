# Renovation Brands refresh (CreditSwan), static site

There is no build step. Everything the page needs is in this folder: index.html, fonts/, favicon.svg and vercel.json.

Deploy:
- Drag this folder onto vercel.com/new, or
- run `npx vercel --prod` from inside this folder (framework: Other, no build command, output directory: .).

The page is marked noindex. Add Vercel password protection if the link must stay private.
