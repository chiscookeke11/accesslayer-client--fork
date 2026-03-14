# Access Layer Client

This folder contains the frontend for Access Layer, a Stellar-based creator keys marketplace where fans buy access keys tied to a creator and unlock perks defined by that creator.

Right now the client is intentionally minimal and renders a simple landing page while the product foundations are being set up.

## Purpose

The client will be responsible for:

- creator and fan onboarding
- wallet connection and transaction prompts
- marketplace browsing and creator profiles
- buying and selling creator keys
- gated access to creator perks and content

## Tech

- Vite
- React
- TypeScript
- Tailwind CSS

## Current state

- root app renders a temporary `Access Layer` landing screen
- old template-specific `coursehub` and `vessel` pages were removed from the app shell
- web3 integration scaffolding still exists in the codebase and can be reconnected when Stellar wallet flows are introduced

## Expected next steps

1. Add a real landing page with creator/fan messaging.
2. Introduce Stellar wallet connection and network config.
3. Build creator listing, profile, and key purchase flows.
4. Add contract integration for reading creator state and submitting buy or sell transactions.

## Commands

```bash
npm install
npm run dev
```

To produce a production build:

```bash
npm run build
```

