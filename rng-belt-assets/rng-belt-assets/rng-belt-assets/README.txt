RNG belt assets (data/ + tex/)
Deploy this folder as a static site, then paste its URL (with trailing slash) into the Framer component.
- Vercel: drag the folder into vercel.com/new or run `vercel --prod` (vercel.json adds CORS).
- Netlify: drop the folder on app.netlify.com/drop (_headers adds CORS).
- Cloudflare Pages: upload the folder (_headers adds CORS).
- GitHub Pages: push the folder; CORS is open by default.
Check: opening <url>/data/anim.json in the browser must show JSON, and the response must include Access-Control-Allow-Origin.
Note: tex/env.hdr is the HDRI; confirm its licence before launch.
