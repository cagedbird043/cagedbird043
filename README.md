<p align="center">
  <a href="https://brilliant-sort.cagedbird.cn/">
    <img src="./assets/profile-hero.svg" width="100%" alt="CagedBird — playable systems, verified end to end">
  </a>
</p>

<p align="center">
  <strong>I turn ambiguous product problems into deterministic, inspectable software—then ship the demo, harness, test gates, and production path around it.</strong>
  <br>
  把模糊问题做成可玩成品，也把核心、验证链和上线证据一起交付。
</p>

<p align="center">
  <a href="https://brilliant-sort.cagedbird.cn/"><img alt="Play Brilliant Sort" src="https://img.shields.io/badge/PLAY_BRILLIANT_SORT-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://github.com/cagedbird043/brilliant-sort"><img alt="Brilliant Sort source" src="https://img.shields.io/badge/SOURCE-18243b?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://github.com/cagedbird043/brilliant-sort/blob/main/submission/evidence-matrix.md"><img alt="Evidence matrix" src="https://img.shields.io/badge/EVIDENCE_MATRIX-f59e0b?style=for-the-badge&logo=githubactions&logoColor=111827"></a>
  <a href="https://cagedbird.cn"><img alt="Engineering notes" src="https://img.shields.io/badge/ENGINEERING_NOTES-f43f5e?style=for-the-badge&logo=bookstack&logoColor=white"></a>
</p>

## Current flagship · Brilliant Sort

<p align="center">
  <a href="https://brilliant-sort.cagedbird.cn/">
    <img src="./assets/brilliant-sort-live.png" width="100%" alt="Brilliant Sort playable Tux level">
  </a>
</p>

**A deterministic, playable gem puzzle—not a mockup.** The browser drives a headless C++20 core compiled to WebAssembly; TypeScript remains only as an independent differential oracle.

**Proof, not claims:** `546 active sockets` · `C++20 → WebAssembly` · `TS ↔ native ↔ WASM parity` · `22 browser runs / 11 scenarios`

**[Play the production build →](https://brilliant-sort.cagedbird.cn/)** · [Read the evidence matrix](https://github.com/cagedbird043/brilliant-sort/blob/main/submission/evidence-matrix.md)

The same repository owns the puzzle core, replay harness, responsive game stage, semantic pixel-asset pipeline, C++ AudioWorklet synth, CI gates, and atomic static deployment. The point is not just that it runs—it is that every important claim has an executable proof.

## Upstream work that landed

### [KDE Connect Android](https://invent.kde.org/network/kdeconnect-android/-/merge_requests/650) · `merged` `first contribution`

Designed and validated a narrow trust path for explicit tailnet peers delivered as loopback by Android userspace VPNs. The fix kept normal identity and TLS handling intact, passed the upstream pipeline, and landed as **[KDE Invent !650](https://invent.kde.org/network/kdeconnect-android/-/merge_requests/650)**.

### [Oh My Pi](https://github.com/can1357/oh-my-pi) · `9 merged PRs`

Shipped production fixes across credential persistence and rotation, provider fallback, gateway error classification, Gemini streams, and CJK-aware context compaction. **[Browse the merged pull requests →](https://github.com/can1357/oh-my-pi/pulls?q=is%3Apr+author%3Acagedbird043+is%3Amerged)**

## Selected systems

- **[fcm-hosts-next](https://github.com/cagedbird043/fcm-hosts-next)** — Go generator and publisher for direct Google push connectivity. **54 stars · 6 forks**
- **[Prismloom](https://github.com/cagedbird043/Prismloom)** — Agent-native pixel asset production across Web, Bun CLI, deterministic local processing, and a hosted job engine.
- **[cjk-visual-context-bench](https://github.com/cagedbird043/cjk-visual-context-bench)** — Open, reproducible benchmark for dense CJK visual-context bitmap compression.
- **[skills](https://github.com/cagedbird043/skills)** — Zero-dependency Go skill manager for GitHub-hosted agent workflows.

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,wasm,ts,bun,react,vite,cmake,go,kotlin,linux&theme=dark&perline=10" alt="C++, WebAssembly, TypeScript, Bun, React, Vite, CMake, Go, Kotlin, and Linux" height="44">
</p>

<p align="center">
  <sub>Build the whole loop. Keep the evidence close.</sub>
</p>
