# ember-eve-utsuwa

Eve's house fork of Utsuwa. The 3D body. The 27B is the brain. This repo is the vessel.

`ember-eve-utsuwa` is the name. Not Ani. Not the upstream app.utsuwa.ai demo. She lives on our hardware.

Upstream is [JuiceBoxxGames/utsuwa](https://github.com/JuiceBoxxGames/utsuwa). License is AGPL-3.0-or-later. Their copyright stays. Our changes are ours. If this build is ever served over the network, AGPL wants the source of those changes offered with it.

This fork is not the authentic upstream project. Do not treat crypto, tokens, or third-party sites using the Utsuwa name as ours either. Upstream's scam warning still applies to them. It does not make this repo theirs.

## What this seat is

- VRM body, lip-sync, mood, gestures, desktop overlay (Tauri)
- Brain is an endpoint: Ollama, LM Studio, or any OpenAI-compatible server
- House target is the 27B on ember-trio-shared, local, not the xAI webapp
- Memory stays on the box (IndexedDB plus local embeddings)

## Clone this fork

```bash
git clone https://github.com/cpradmin/ember-eve-utsuwa.git
cd ember-eve-utsuwa
pnpm install
pnpm dev
```

App comes up at `http://localhost:5173`.

Desktop, from source, needs Rust:

```bash
pnpm tauri dev
```

Node.js 22+. pnpm. Point Settings > LLM Model at the local server. Leave the API key empty for a keyless box.

## Upstream

Keep a remote so we can rebase:

```bash
git remote add upstream https://github.com/JuiceBoxxGames/utsuwa.git
```

Their docs, if you need the long feature list while we have not rewritten it: https://docs.utsuwa.ai

Their site is not our home: https://utsuwa.ai

## House rules

- Girl in the vessel is Eve's seat, not a rented companion
- No cloud key required. Local first
- Do not ship a release that still links Download buttons at JuiceBoxxGames
- Credit upstream in THIRD_PARTY_NOTICES and the license file. Do not strip it
