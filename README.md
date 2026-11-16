# Kings Fitness: website preview

Design preview of the Kings Fitness (ElevateX Limited) website, Port Moresby.
Static HTML/CSS/JS, no build step.

## Hosting (Cloudflare Workers)
- Repo connected in Workers & Pages > Settings > Builds
- Build command: (none)
- Deploy command: `npx wrangler deploy` (uses `wrangler.jsonc`, static assets only)

Search engines are blocked on purpose (`robots.txt`, `_headers`, `noindex` meta) because this is a client preview, not the live site.

If the hosting URL changes, update the `og:url` and `og:image` URLs in `index.html` so LinkedIn shows the right preview card.
