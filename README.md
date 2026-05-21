<div align="center">

# Hey, I'm slauko

I build product-focused web apps with Nuxt and TypeScript — and an autonomous daemon that ships PRs for me at 3 AM.

<a href="https://github.com/SlaukoScript">
  <img src="https://raw.githubusercontent.com/SlaukoScript/.github/main/assets/logo.png" alt="SlaukoScript" width="420" />
</a>

### Current focus: SlaukoScript

A 10-repo product ecosystem — shared TypeScript packages + per-app GHCR images + a central docker-compose. 
Self-hosted on a VPS.

Currently shipping **Moderation** (cross-platform Discord + Twitch moderation), **GymTrack** (offline-first gym tracking PWA), and a self-hosted **AI gateway** that powers both the chat dashboard and an in-house Claude-Code-compatible agentic CLI.

[![Website](https://img.shields.io/badge/slaukoscript.com-F97316?style=for-the-badge&logo=googlechrome&logoColor=white)](https://slaukoscript.com)
[![Org](https://img.shields.io/badge/SlaukoScript-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SlaukoScript)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/nVGAfRg8Md)
[![Feedback](https://img.shields.io/badge/Feedback-Issues-22C55E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SlaukoScript/feedback/issues)

</div>

<div align="center">

## What's running today

🌐 **Apps** — each in its own repo with its own CI/CD, deployed as a GHCR image
```
gymtrack     ·     moderation     ·     web     ·     ai (chat + gateway + cli)
```

📦 **Shared packages** — published as `0.0.0-<sha>-snapshot` to GitHub Packages
```
core  ·  platform  ·  server  ·  ui  ·  tooling
```

🐳 **Central deploy** — one `docker-compose.yml` in `slaukoscript/infra` pulls every GHCR image. `compose-up.sh` reloads everything in one command.

🤖 **Autonomous CI daemon** — sweeps every repo on a cadence, opens improvement PRs. Speaks to the in-house AI gateway via the `slauko agent` CLI (drop-in compatible with Claude Code's flag surface).

🧠 **AI gateway** — OpenAI-compat proxy at `ai.slaukoscript.com/api` routing to Scaleway-hosted Qwen 3 models. Same gateway powers VSCode/Continue, the chat dashboard, and the daemon's sweeps.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nitro](https://img.shields.io/badge/Nitro-FFA500?style=flat-square&logo=nitro&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Turbo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=pinia&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GHCR](https://img.shields.io/badge/GHCR-181717?style=flat-square&logo=github&logoColor=white)
![GitHub%20Actions](https://img.shields.io/badge/Self--hosted%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Scaleway](https://img.shields.io/badge/Scaleway-4F0599?style=flat-square&logo=scaleway&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen3-7B61FF?style=flat-square)

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=slauko&theme=github-dark-blue&hide_border=true&background=0D1117&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=c9d1d9&dates=555555" alt="GitHub streak stats for slauko" />
</div>
