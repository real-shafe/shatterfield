# Shatterfield

A colourful 3D arcade shooter. Fly an interceptor through a glowing asteroid field and shatter the rocks before they reach your hull.

**Play:** https://shatterfield.shafe.dev

- Lava, ice, crystal and gold asteroids that split apart, with sparks, shockwaves and hit-stop
- Score multiplier up to ×8, gem power-ups, a screen-clearing Nova and a barrel roll
- A new planet sector every 55 seconds and a synthwave soundtrack generated in the browser

**Controls:** mouse or WASD to steer, hold click or Space to fire, E or right-click for Nova, Shift to roll. On phones, drag to steer.

Single `public/index.html` using Three.js from a CDN.

## Deploy

Served by a Cloudflare Worker with static assets (`wrangler.jsonc`). Deploy with:

```bash
npx wrangler deploy
```
