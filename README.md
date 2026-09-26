<div align="center">

# Hey, I'm slauko

I build Linux systems tooling and web platforms, with a stubborn preference for systems that can actually run locally.

<img src="https://github.com/SlaukoKit.png?size=256" alt="SlaukoKit organization icon" width="160" />

### Currently working on: SlaukoKit

From kernel internals to the desktop surface.

Linux internals · C / C++ · Wayland · Systems programming

</div>

SlaukoKit is my experimental Linux toolkit. It combines a kernel module,
userspace client and CLI, and an application SDK for interactive gamepacks.
Everything ships from one repository, `slaukokit`.

The SDK includes:

- `libslauko` for sessions and typed reads
- `libslkscript` for sandboxed Lua scripts, events, actions, and drawing commands
- `libslkapp` for settings, menus, gates, and worker/UI coordination
- `libslkui` for Wayland/X11 surfaces, input, and rendering

A gamepack is one directory: a bounded C reader, an offset recipe and its pack
Lua. Settings, menus and profiles are declared in Lua, the C side owns capture.
Feature scripts own their rules, profiles, settings, and visuals. The baseline
is one repository with one verification gate, `make verify`. The implementation
repository is private.

---

<div align="center">

  <img src="https://github-readme-streak-stats.herokuapp.com?user=slauko&theme=github-dark-blue&hide_border=true&background=0D1117&ring=F97316&fire=F97316&currStreakLabel=F97316&sideLabels=c9d1d9&dates=555555" alt="GitHub streak stats for slauko" />
</div>
