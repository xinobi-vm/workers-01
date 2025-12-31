# Workers 101

## Wrangler CLI Commands

- Create a Project
  $ npm create cloudflare

- npx wrangler login

- npx wrangler whoami

- npm run deploy - Deploys the worker to your Cloudflare Account

- npm run dev - Runs the worker in your local development server, http://localhost:8787
  - This uses miniflared - open source, local simulator to mimic Cloudflare environment
  - Can simulate Durable Objects, D1, R2 and Queues
