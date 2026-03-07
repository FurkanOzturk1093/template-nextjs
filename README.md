# DeployWise — Next.js Template

A production-ready Next.js starter, pre-configured for one-click deployment to your VPS with [DeployWise](https://deploywise.dev).

## What's Included

- Next.js 15 with App Router and TypeScript
- Tailwind CSS ready
- ESLint pre-configured
- Optimized for PM2 + Nginx deployment

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy with DeployWise

1. Push this repo to GitHub
2. Open [deploywise.dev/dashboard](https://deploywise.dev/dashboard)
3. Add your VPS → Create a project → Select this repo
4. Click **Deploy**

DeployWise automatically runs `npm run build`, starts with PM2, configures Nginx, and issues a free SSL certificate. Live in under 60 seconds.

## Project Structure

```
├── app/
│   ├── layout.tsx    # Root layout
│   ├── page.tsx      # Home page
│   └── globals.css   # Global styles
├── public/           # Static assets
└── next.config.ts    # Next.js configuration
```

## Learn More

- [Deploy Next.js to VPS Guide](https://deploywise.dev/guides/deploy-nextjs-to-vps)
- [DeployWise Docs](https://deploywise.dev/docs)
- [Next.js Documentation](https://nextjs.org/docs)

---

Deployed with [DeployWise](https://deploywise.dev) — free, open source.
