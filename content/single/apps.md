---
title: "Apps"
description: "macOS apps crafted for performance and simplicity"
---

<style>
  .app-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 2rem; }
  .app-card { border: 1px solid hsl(var(--border)); border-radius: 16px; padding: 2rem; transition: transform .2s, box-shadow .2s; background: hsl(var(--card)); }
  .app-card:hover { transform: translateY(-3px); box-shadow: 0 8px 24px rgba(0,0,0,.12); }
  .app-icon { width: 88px; height: 88px; border-radius: 20px; margin-bottom: 1rem; }
  .app-name { font-size: 1.3rem; font-weight: 700; margin: 0 0 .35rem; color: hsl(var(--foreground)); }
  .app-desc { color: hsl(var(--muted-foreground)); font-size: .9rem; margin: 0 0 1rem; line-height: 1.6; }
  .app-features { list-style: none; padding: 0; margin: 0 0 1.25rem; }
  .app-features li { font-size: .82rem; color: hsl(var(--muted-foreground)); padding: .2rem 0; }
  .app-features li::before { content: "• "; color: hsl(var(--primary)); }
  .app-link { display: inline-block; background: hsl(var(--primary)); color: hsl(var(--primary-foreground)); padding: .5rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: 600; font-size: .9rem; transition: opacity .15s; }
  .app-link:hover { opacity: .85; }
  .platform-tag { display: inline-block; font-size: .72rem; padding: .2rem .6rem; border-radius: 6px; background: hsl(var(--muted)); color: hsl(var(--muted-foreground)); margin-right: .4rem; }
</style>

## macOS Apps

<div class="app-grid">

<div class="app-card">
  <img src="/apps/icons/tubekit.png" alt="TubeKit" class="app-icon" />
  <h3 class="app-name">TubeKit</h3>
  <span class="platform-tag">macOS</span><span class="platform-tag">Safari Extension</span>
  <p class="app-desc">
    A powerful Safari Web Extension that transforms your YouTube experience with 11 customizable features — auto unmute, skip ads, remove shorts, auto best quality, keep original language, smart recommendations, and more.
  </p>
  <a href="https://apps.apple.com/br/app/tubekit/id6761668334" class="app-link">App Store →</a>
</div>

<div class="app-card">
  <img src="/apps/icons/clustrk8s.png" alt="ClustrK8s" class="app-icon" />
  <h3 class="app-name">ClustrK8s</h3>
  <span class="platform-tag">macOS</span>
  <p class="app-desc">
    Native macOS Kubernetes cluster monitoring — nodes, workloads, events, and metrics in real time. Smart alerting, iCloud sync across devices, and a clean interface designed for daily operations.
  </p>
  <a href="https://apps.apple.com/br/app/clustrk8s/id6759920543" class="app-link">App Store →</a>
</div>

<div class="app-card">
  <img src="/apps/icons/overseerdash.png" alt="OverseerDash" class="app-icon" />
  <h3 class="app-name">OverseerDash</h3>
  <span class="platform-tag">macOS</span>
  <p class="app-desc">
    Modern real-time system monitor built with SwiftUI. Track CPU, memory, GPU, disk, network, battery, Bluetooth, and running processes with a customizable dashboard. No daemons, no bloat.
  </p>
  <a href="https://apps.apple.com/br/app/overseerdash/id6759227616" class="app-link">App Store →</a>
</div>

<div class="app-card">
  <img src="/apps/icons/harbordb.png" alt="HarborDB" class="app-icon" />
  <h3 class="app-name">HarborDB</h3>
  <span class="platform-tag">macOS</span>
  <p class="app-desc">
    Native macOS database GUI with PostgreSQL support via PostgresNIO. Protocol-based architecture designed for extensibility — MySQL, Redis, and more on the roadmap.
  </p>
  <a href="https://apps.apple.com/br/app/harbordb/id6758565656" class="app-link">App Store →</a>
</div>

</div>

## Coming Soon

- **iOS & iPadOS** versions of all apps
- **Apple TV** dashboard views
- **Apple Watch** companion widgets

## Support

Questions or feedback? Reach out at [support@lbenicio.dev](mailto:support@lbenicio.dev).
