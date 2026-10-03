<div align="center">

# slauko

Systems and security engineering on Linux: self-hosted, outbound-only, fail-closed.

</div>

## What I work on

I build self-hosted infrastructure and desktop software for Linux, mostly in
Rust and TypeScript. I care most about the unglamorous parts that make a system
trustworthy: which side opens each connection, where every secret lives, what
happens when a delivery is uncertain, and how an update proves where it came from.

## Currently: SlaukoKit Network

<p align="center">
  <a href="https://slaukokit.dev">
    <img src="https://github.com/SlaukoKit.png?size=256" alt="SlaukoKit" width="140" />
  </a>
</p>

A private workspace that connects an AI agent across several of my own computers
without opening a single port on any of them.

- **Computers dial out** over TLS, and each has its own credential that can be revoked
- **Passkey sign-in**, and the hub credential never reaches the browser
- **Signed, staged updates** that are verified before they're activated atomically
- **Journaled dispatch**: prompt IDs are reserved before sending and never retried blindly
- **End-to-end acceptance tests** that start the real binaries, not mocks

The architecture, threat model, known limits and engineering notes are published
at **[slaukokit.dev](https://slaukokit.dev)**. The code is private for now.

## Toolbox

Rust · TypeScript · Next.js · Tauri · SQLite · systemd · nftables · Linux

[slaukokit.dev](https://slaukokit.dev) · [SlaukoKit on GitHub](https://github.com/SlaukoKit)

---

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=slauko&theme=github-dark-blue&hide_border=true&background=0D1117&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=c9d1d9&dates=555555" alt="GitHub streak stats for slauko" />
</p>
