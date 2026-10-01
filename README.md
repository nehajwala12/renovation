# Renovation Brands · Diagnostic preview (CreditSwan)

Static, single-file site. No build step.

Password-protected: the page content is AES-256 encrypted inside index.html and only decrypts in the browser with the password (Renovation2026). The password stays valid for the browser tab session.

Deploy:
- Vercel dashboard: New Project → import this folder (Framework preset: Other, no build command, output directory `.`), or
- CLI: `cd renovation-brands-diagnostic && npx vercel --prod`

`vercel.json` sets noindex headers so the preview stays out of search engines.
Deep links work as `/#freight` or `/#freight/fr-economics`.
