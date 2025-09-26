# Genie4 TikTok OAuth Starter

**Endpoints**
- Home: `/`
- Start OAuth: `/auth/tiktok`
- Callback: `/auth/tiktok/callback`

**Environment Variables (Vercel → Settings → Environment Variables)**
- `TIKTOK_CLIENT_KEY`
- `TIKTOK_CLIENT_SECRET`
- `TIKTOK_SCOPES` (e.g. `user.info.basic,user.info.stats,video.list`)

**TikTok Redirect URI to set in Developer Console**
- `https://YOUR-DOMAIN.vercel.app/auth/tiktok/callback`

After TikTok approves, clicking "Login with TikTok" will redirect back to the callback and render your profile, stats, and last few public videos.
