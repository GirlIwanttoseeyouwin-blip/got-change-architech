# Got Change AI Twin

Rae — Rashea's AI Twin — deployed for Got Change Skool members.

## Setup
1. `npm install`
2. Add `ANTHROPIC_API_KEY` as an environment variable (locally in `.env.local`, or in Vercel project settings)
3. `npm run dev` to run locally, or deploy to Vercel

## Structure
- `pages/index.js` — Rae's chat interface (the component)
- `pages/api/chat.js` — secure backend that talks to Anthropic (keeps the API key server-side only)
