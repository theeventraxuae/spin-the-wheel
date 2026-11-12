# SKMC X Cincinatte - Spin Wheel Kiosk (compiled build)

Compiled static export (Next.js 15, 1080x1920 portrait kiosk) of the live site at https://kiosk.theeventrax.com.

NOTE: This repo contains the COMPILED output only (minified). The original source was lost in a sandbox reset.

## Deploy
Upload this folder as-is to any static host (Cloudflare Pages project `skmc-x-cincinatte`):

    npx wrangler pages deploy . --project-name skmc-x-cincinatte --branch main

## Defaults baked in
- Home logo: https://youreventhub.ae/General_images/logo.png
- Break banner: https://youreventhub.ae/General_images/breakimage.png
- Admin: long-press the logo for 5 seconds
