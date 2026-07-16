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
  <a href="https://brilliant-sort.cagedbird.cn/"><img alt="Play Brilliant Sort" src="https://img.shields.io/badge/PLAY_BRILLIANT_SORT-0ea5e9?style=for-the-badge&logo=googleplay&logoColor=white"></a>
  <a href="https://github.com/cagedbird043/brilliant-sort"><img alt="Brilliant Sort source" src="https://img.shields.io/badge/SOURCE-18243b?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://github.com/cagedbird043/brilliant-sort/blob/main/submission/evidence-matrix.md"><img alt="Evidence matrix" src="https://img.shields.io/badge/EVIDENCE_MATRIX-f59e0b?style=for-the-badge&logo=checkmarx&logoColor=111827"></a>
  <a href="https://cagedbird.cn"><img alt="Engineering notes" src="https://img.shields.io/badge/ENGINEERING_NOTES-f43f5e?style=for-the-badge&logo=bookstack&logoColor=white"></a>
</p>

## Current flagship · Brilliant Sort

<table>
  <tr>
    <td width="62%">
      <a href="https://brilliant-sort.cagedbird.cn/">
        <img src="./assets/brilliant-sort-live.png" width="100%" alt="Brilliant Sort playable Tux level">
      </a>
    </td>
    <td width="38%" valign="top">
      <strong>A deterministic, playable gem puzzle—not a mockup.</strong>
      <br><br>
      The browser drives a headless C++20 core compiled to WebAssembly. TypeScript remains only as an independent differential oracle.
      <br><br>
      <code>546 active sockets</code><br>
      <code>C++20 → WebAssembly</code><br>
      <code>TS ↔ native ↔ WASM parity</code><br>
      <code>22 browser runs / 11 scenarios</code>
      <br><br>
      <a href="https://brilliant-sort.cagedbird.cn/"><strong>Play the production build →</strong></a>
    </td>
  </tr>
</table>

The same repository owns the puzzle core, replay harness, responsive game stage, semantic pixel-asset pipeline, C++ AudioWorklet synth, CI gates, and atomic static deployment. The point is not just that it runs—it is that every important claim has an executable proof.

## Upstream work that landed

<table>
  <tr>
    <td width="24%" valign="top">
      <strong>KDE Connect Android</strong><br>
      <code>merged · first contribution</code>
    </td>
    <td width="76%">
      Designed and validated a narrow trust path for explicit tailnet peers delivered as loopback by Android userspace VPNs. The fix kept normal identity and TLS handling intact and passed the upstream pipeline.
      <br>
      <a href="https://invent.kde.org/network/kdeconnect-android/-/merge_requests/650"><strong>KDE Invent !650 →</strong></a>
    </td>
  </tr>
  <tr>
    <td width="24%" valign="top">
      <strong>Oh My Pi</strong><br>
      <code>9 merged PRs</code>
    </td>
    <td width="76%">
      Shipped production fixes across credential persistence and rotation, provider fallback, gateway error classification, Gemini streams, and CJK-aware context compaction.
      <br>
      <a href="https://github.com/can1357/oh-my-pi/pulls?q=is%3Apr+author%3Acagedbird043+is%3Amerged"><strong>Browse merged pull requests →</strong></a>
    </td>
  </tr>
</table>

## Selected systems

| Project | What shipped | Signal |
| :--- | :--- | ---: |
| **[fcm-hosts-next](https://github.com/cagedbird043/fcm-hosts-next)** | Go generator and publisher for direct Google push connectivity | **54 stars · 6 forks** |
| **[Prismloom](https://github.com/cagedbird043/Prismloom)** | Agent-native pixel asset production: Web, Bun CLI, deterministic local pipeline, and hosted job engine | **Apache-2.0** |
| **[cjk-visual-context-bench](https://github.com/cagedbird043/cjk-visual-context-bench)** | Open benchmark for dense CJK visual-context bitmap compression | **Reproducible benchmark** |
| **[skills](https://github.com/cagedbird043/skills)** | Zero-dependency Go skill manager for GitHub-hosted agent workflows | **Single binary** |

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,wasm,ts,bun,react,vite,cmake,go,kotlin,linux&theme=dark&perline=10" alt="C++, WebAssembly, TypeScript, Bun, React, Vite, CMake, Go, Kotlin, and Linux" height="44">
</p>

<p align="center">
  <sub>Build the whole loop. Keep the evidence close.</sub>
</p>
