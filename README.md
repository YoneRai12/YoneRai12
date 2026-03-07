<h1 align="center">YoneRai12</h1>

<p align="center">
  <strong>自分のPCに住むAIを作る開発者</strong>
</p>

<p align="center">
  <em>Builder of AI that lives on your own PC.</em>
</p>

<p align="center">
  Building <strong>YonerAI</strong> and related local-first / hybrid AI systems.
</p>

<p align="center">
  <a href="#-日本語プロフィール">
    <img src="https://img.shields.io/badge/JP-日本語-2563EB?style=for-the-badge" alt="Japanese Profile" />
  </a>
  <a href="#-english-profile">
    <img src="https://img.shields.io/badge/EN-English-111827?style=for-the-badge" alt="English Profile" />
  </a>
</p>

<p align="center">
  <a href="https://yonerai.com">
    <img src="https://img.shields.io/badge/Website-yonerai.com-2563EB?style=for-the-badge" alt="Website" />
  </a>
  <a href="https://github.com/YoneRai12/YonerAI">
    <img src="https://img.shields.io/badge/Project-YonerAI-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="Project YonerAI" />
  </a>
  <a href="mailto:hello@yonerai.com">
    <img src="https://img.shields.io/badge/Mail-hello%40yonerai.com-16A34A?style=for-the-badge&logo=gmail&logoColor=white" alt="Mail" />
  </a>
  <a href="https://x.com/YoneRai12">
    <img src="https://img.shields.io/badge/X-@YoneRai12-111111?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://qiita.com/YoneRai12">
    <img src="https://img.shields.io/badge/Qiita-YoneRai12-55C500?style=for-the-badge&logo=qiita&logoColor=white" alt="Qiita" />
  </a>
</p>

> `yonerai.com` は現在メンテナンス中です。最大で **2026年3月31日** まで継続予定ですが、不定期に早めに終了する場合があります。
> `yonerai.com` is currently under maintenance. It may continue until **March 31, 2026** at the latest, but maintenance may also end earlier without a fixed schedule.

---

## 🇯🇵 日本語プロフィール

自分のPCに住むAIを作っています。

今いちばん力を入れているのは **YonerAI** です。
YonerAI は、まず自分のPCで動くことを前提にした AI システムで、単なるチャットUIではなく、

- Discord Bot
- Web UI
- Core
- Relay
- tools / skills
- approvals / audit

まで含めて組んでいます。

### 今やっていること

- **YonerAI の公開版 Node を整理すること**
  - ユーザーのPCで動く、配布可能な YonerAI 側を整備中
- **YonerAI の private 側を分離すること**
  - VPS、商業運用、公式Web、運用AI を分けて設計中
- **Discord / PC / operator 系の AI 体験を作ること**
  - 日常で使える AI と、実際に動く AI をつなげたい
- **ローカル実行と hybrid 構成の両立**
  - 自分のPCに住むAIと、VPSの control plane を両立できる形を考えている

### Flagship Project

#### [YonerAI](https://github.com/YoneRai12/YonerAI)

YonerAI は、ローカルファーストな AI Node / AI operator を目指して作っているプロジェクトです。

今の公開版では主に次を扱っています。

- Discord ベースの AI runtime
- FastAPI ベースの admin / setup API
- optional Core による routing / reasoning 分離
- web chat / dashboard UI
- Relay を使った pairing / proxy の土台
- tool 実行の risk scoring / approval / audit
- MCP や local skills による拡張

長期的には、

- public 側の配布 Node
- private 側の VPS / 商業運用 / `yonerai.com`

を明確に分けていく方針です。

---

## 🌍 English Profile

I build AI that lives on your own PC.

My main project right now is **YonerAI**.
It is a local-first AI system designed to run on a personal PC first, while still growing toward hybrid and platform-style deployment later.

YonerAI is not just a chat UI. It currently includes:

- a Discord-based runtime
- web/admin surfaces
- an optional Core process
- relay foundations
- tools / skills
- approvals / audit boundaries

### Current Focus

- making the public YonerAI node cleaner and easier to distribute
- separating the private VPS / commercial / official web side
- building AI experiences that connect Discord, PC workflows, and operator-style execution
- keeping both local-first and hybrid deployment paths viable

---

## Public Projects

### [YonerAI](https://github.com/YoneRai12/YonerAI)
Local-first AI node / AI operator project.

### [Minecraft-AI-Bedrock-Edition](https://github.com/YoneRai12/Minecraft-AI-Bedrock-Edition)
Experiments around Minecraft and AI.

### [RTX5090-DebugSystem](https://github.com/YoneRai12/RTX5090-DebugSystem)
GPU / runtime / debugging oriented experiments.

### [Discord-Measures-against-vandalism-YoneRai12](https://github.com/YoneRai12/Discord-Measures-against-vandalism-YoneRai12)
Security / anti-vandalism bot code for Discord communities.

---

## Interests

- local-first AI
- Discord-native AI experiences
- AI agents / tool calling / approval / audit
- Node + Relay + Core separation
- Windows / VPS / hybrid deployment
- practical, messy, real-world automation

---

## Tech Stack

| Area | Main Stack |
| --- | --- |
| Languages | Python, TypeScript / JavaScript |
| AI / Runtime | LLM routing, tool calling, MCP, local-first AI |
| Backend | FastAPI, WebSocket, relay patterns |
| Frontend | Next.js, dashboard / web UI |
| Infra / Ops | GitHub Actions, VPS, Cloudflare, deployment flows |
| Other | Discord bots, automation, GPU / local runtime work |

---

## Build Philosophy

- build things I actually want to use
- think in terms of systems, not just wrappers
- keep public and private boundaries explicit
- prioritize working software
- leave room for future derived products

---

## Links

- GitHub: [YoneRai12](https://github.com/YoneRai12)
- Website: [yonerai.com](https://yonerai.com)
- YonerAI: [github.com/YoneRai12/YonerAI](https://github.com/YoneRai12/YonerAI)
- Mail: [hello@yonerai.com](mailto:hello@yonerai.com)
- Qiita: [qiita.com/YoneRai12](https://qiita.com/YoneRai12)
- X: [x.com/YoneRai12](https://x.com/YoneRai12)

---

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=YoneRai12&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="170" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=YoneRai12&theme=tokyonight" alt="GitHub Stats" height="170" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=YoneRai12&theme=tokyonight" alt="Top Languages" height="170" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=YoneRai12&theme=tokyonight" alt="Most Commit Language" height="170" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YoneRai12&theme=tokyonight" alt="Profile Summary" width="100%" />
</p>
