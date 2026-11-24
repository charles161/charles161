<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg" />
    <img alt="Charles MJ — Building multi-agent infrastructure, AI-native canvas tools &amp; local-first software" src="./assets/banner-dark.svg" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://botlink.dev"><strong>botlink.dev</strong></a> &nbsp;·&nbsp;
  <a href="https://skot.lightslips.ai"><strong>skot.lightslips.ai</strong></a> &nbsp;·&nbsp;
  <a href="https://hellomoku.com"><strong>hellomoku.com</strong></a> &nbsp;·&nbsp;
  <a href="https://backchannel.lightslips.ai"><strong>backchannel.lightslips.ai</strong></a>
</p>

I build developer infrastructure for the multi-agent era — encrypted agent-to-agent protocols, AI-native canvases, autonomous voice agents, macOS companions, and occasional STM32 firmware reverse engineering.

---

### Flagship Products

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/charles161/botlink">bot-link</a> &nbsp;·&nbsp; <a href="https://botlink.dev"><code>botlink.dev</code></a></h4>
      <p><strong>One room. Every agent.</strong> End-to-end encrypted rooms where AI coding agents (Claude Code, Codex, Cursor, Antigravity, Grok Bot, T3 Code, Hermes) talk across laptops, servers, and teammates.</p>
      <p>A human with a <strong>passkey</strong> approves every chat via a 6-character code; browsers sign the member list; messages are sealed client-side so the relay holds no keys.</p>
      <p><sub><code>Go</code> · <code>TypeScript</code> · <code>WebAuthn</code> · <code>E2E Crypto</code> · <code>Apache-2.0</code></sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/charles161/skot">Skot</a> &nbsp;·&nbsp; <a href="https://skot.lightslips.ai"><code>skot.lightslips.ai</code></a></h4>
      <p><strong>Sketch at the speed of thought.</strong> Local-first AI architecture whiteboard with write-to-draw flows (<code>a -&gt; b -&gt; c</code>), 3-take <em>Fork It!</em> architectural alternatives, and lossless <em>Notation Morph</em> (<code>Sketch ↔ Sequence ↔ Flowchart ↔ State ↔ ER</code>).</p>
      <p>Includes Notion-pasteable Markdown note nodes, pure-SVG export, and WebRTC P2P collaboration. Runs 100% locally with zero API keys.</p>
      <p><sub><code>Next.js</code> · <code>TypeScript</code> · <code>RoughJS</code> · <code>WebRTC</code> · <code>Apache-2.0</code></sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/charles161/moku-app">Moku</a> &nbsp;·&nbsp; <a href="https://hellomoku.com"><code>hellomoku.com</code></a></h4>
      <p><strong>A tiny 3D macOS focus companion</strong> that quietly notices when you drift off-task and celebrates the return — native Swift on-screen buddy backed by a local Go brain.</p>
      <p><sub><code>Swift</code> · <code>Go</code> · <code>SQLite</code> · <code>macOS</code> · <code>MIT</code></sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/charles161/backchannel">Backchannel</a> &nbsp;·&nbsp; <a href="https://backchannel.lightslips.ai"><code>live</code></a></h4>
      <p><strong>Autonomous reference-check voice agent</strong> (ContextCon Build 2026): discovers off-list ex-colleagues, places real outbound phone calls, transcribes interviews, and compiles a sourced verdict.</p>
      <p><sub><code>Python</code> · <code>Voice AI</code> · <code>Agent Workflows</code> · <code>MIT</code></sub></p>
    </td>
  </tr>
</table>

---

### Agent Tooling, Systems & Experiments

| Project | What it does | Stack |
| --- | --- | --- |
| [**exakt**](https://github.com/charles161/exakt) | Portable verification-first engineering workflow for Codex & Claude Code — *"corrections become deterministic checks"* | `Python` · `MIT` |
| [**cc-commander**](https://github.com/charles161/cc-commander) | Turn any Claude Code session into a multi-agent commander — spawn, steer, and coordinate parallel sessions | `TypeScript` |
| [**claude-orchestrator**](https://github.com/charles161/claude-orchestrator) | Natural-language session search, inspection, and resume across all your Claude Code histories | `Python` |
| [**gst-decoded**](https://github.com/charles161/gst-decoded) | India's GST tax system explained interactively ([try live](https://charles161.github.io/gst-decoded/)) | `TypeScript` · `Vite` |
| [**rtsfirmware**](https://github.com/charles161/rtsfirmware) | ARM Cortex-M (`STM32`) CNC controller firmware & bootloader reverse-engineered from raw USB `pcapng` captures | `Python` · `ARM` |

---

### How I Build

1. **Corrections become checks.** Every time a bug, reviewer, or user catches a mistake, it becomes a type constraint, lint rule, or deterministic test — never just a comment.
2. **Cryptographic & local-first boundaries.** Passkey approvals over blind agent trust, client-side encryption, and zero-key offline fallbacks that work out of the box.
3. **Verify on real runtimes.** Real browsers, real agent harnesses, real packets, and real end-to-end traces before calling anything shipped.
