# THE LATVERIAN ARCHIVE — Avinash K

An original 3D portfolio: a technological fortress transformed into the personal
engineering headquarters of **Avinash K — Cyber Security Student & Web Developer**
(B.E. Cyber Security, SRM Valliammai Engineering College, Chennai).

No templates. No copied artwork. Stone, iron, bronze, emerald.

## World map

| Gate | Chamber |
|------|---------|
| 01 GATE | Cinematic hero + fortress exterior |
| 02 ARCHITECT | About + rotating engineering core + engraved records |
| 03 ARMORY | Interactive skills arsenal (web / development / security) |
| 04 FORGE | 5 project files with inspection vaults + architecture diagrams |
| 05 CHRONICLES | Education + milestone timeline |
| 06 ARCHIVE | Honest certification records + downloadable identification file |
| 07 CONTACT | Secure transmission terminal (validated, mailto-routed) |

## Run

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy

GitHub Actions (`.github/workflows/deploy.yml`) builds `dist/` and deploys to
GitHub Pages on every push to `main`:

Live: **https://avinashk08408.github.io/TECFEST-AIGNITE/**

Vite `base` is `/TECFEST-AIGNITE/` so all assets resolve under the project path.

## Engineering notes

- React + Vite + TypeScript, Three.js + React Three Fiber (no model files — all
  fortress geometry is hand-built primitives: towers, walls, keep, cores, mountains)
- 3D is lazy-loaded and code-split; CSS fortress fallback when WebGL is missing
- Reduced-motion visitors get a static scene and no loader
- Scroll-linked camera dolly, pointer parallax, fog + dust + ember particles
- Secrets: touch the gate seal three times; `fortress("open")` in the console
