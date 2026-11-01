# Teman

A listening map of Southeast Asian selectors, by feeling.

## Put it online (first time)

You need Node.js installed (nodejs.org, the LTS version).

```
cd teman-wrangler
npm install
npx wrangler login      # opens your browser to sign in to Cloudflare
npm run deploy
```

Wrangler prints your address when it's done, something like
`https://teman.<your-subdomain>.workers.dev`.

## Update it later

Replace `public/index.html` with the new version, then run `npm run deploy` again.
The address stays the same.

## Try it on your computer first

```
npm run preview
```

Then open the address it prints (usually http://localhost:8787).

## Your own domain

In the Cloudflare dashboard: Workers & Pages → teman → Settings → Domains & Routes → Add.
