# DevFinder

A React Native (Expo + TypeScript) MVP app that helps developers find peers in their geographic area. Built for SODV2251 — Mobile Application Development.

## Project structure

```
project1/
  App.tsx          # Entry point
  app.json         # Expo config (name, slug, icons)
  index.ts         # Registers the root component
  tsconfig.json    # TypeScript config
  assets/          # Icons and splash images
```

## Running the app

```bash
npm run android   # Android emulator or device
npm run ios       # iOS (macOS only)
npm run web       # Browser
```

Expo docs (v56): https://docs.expo.dev/versions/v56.0.0/

## Architecture notes

- Uses mock data — no backend required. Each institution deploying this app is expected to provide their own backend service.
- Navigation: React Navigation (to be added)
- Screens: Feed (developer list), ProfileDetail, Filter

## Git workflow

- `main` — stable, reviewed code only
- Feature branches off main, e.g. `feat/developer-list`
- All changes merged via pull request with peer review
