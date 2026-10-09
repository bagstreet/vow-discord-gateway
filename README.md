# Vow Discord Gateway relay

Forwards Discord direct messages to the Vow API and posts the reply. Part of the Vow project (`bagstreet/vow`, `apps/discord-gateway`).

Env: `DISCORD_BOT_TOKEN` (required), `VOW_API_URL` (default `https://vow-livid.vercel.app`). Deploy on any Node 20+ host; Render free web service works with `npm install` / `node worker.mjs`.
