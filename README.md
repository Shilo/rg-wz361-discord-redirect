# rg-wz361-discord-redirect

![RG War Zone 361 icon](https://cdn.discordapp.com/icons/1443735922649862247/86447bbf5b228fdd4d1995b99d861bad.webp)

Tiny static page that immediately redirects visitors to the 🔫RG War Zone 361 Discord. It also shows a quick fallback link and Discord icon in case auto-redirect is blocked.

## How it works
- Plain HTML/CSS; no build or dependencies.
- Uses a flex layout to center the icon and text.
- Manual link provided for users if the redirect doesn’t fire.

## Deploying
- Serve `index.html` from GitHub Pages (or any static host).
- Point your custom domain (e.g., `wz361.xyz`) at the host.

## Editing
- Update the Discord invite URL and icon URL in `index.html` if they change.
- Tweak the copy or styles directly in the same file; no tooling required.
