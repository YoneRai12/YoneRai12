<h1 align="center">YoneRai12</h1>

<p align="center">
  <strong>YonerAI を作っています。</strong>
</p>

<p align="center">
  <em>Building a provider-independent AI runtime foundation.</em>
</p>

<p align="center">
  AI を、1社のUIではなく、公式・ローカル・self-host を横断して続く実行基盤へ。
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
  <a href="https://github.com/YoneRai12/YonerAI">
    <img src="https://img.shields.io/badge/YonerAI-provider--independent-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="YonerAI" />
  </a>
  <a href="https://yonerai.com">
    <img src="https://img.shields.io/badge/Website-yonerai.com-2563EB?style=for-the-badge" alt="Website" />
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

---

## 🇯🇵 日本語プロフィール

AI を、単なるチャット UI ではなく、長く使い続けられる実行基盤として作っています。

現在の中心プロジェクトは **YonerAI** です。

YonerAI は、公式サービス、ローカル環境、self-host 環境のどれを使っても、できるだけ同じ AI 体験と同じ契約で動かすための **provider-independent AI runtime foundation** です。

単なる Discord Bot でも、単なる model router でもありません。

設計の中心に置いているものは、モデルそのものよりも、

- provider independence
- same experience across official / local / self-host
- public / private / control-plane boundary
- API / CLI / Web / Discord surface separation
- typed action / approval / audit
- local Core API
- mock / offline / loopback local LLM runtime
- self-evolution as approval-gated product intelligence

です。

### 今の YonerAI

現在の公開 repo は、完成済み製品ではなく、公開可能な core / contract / runtime boundary を育てている段階です。

今の public MVP で扱っている主な範囲は次です。

- local Core API health smoke
- mock / offline message contract
- loopback-only local LLM conversation path
- CLI client
- Web Chat MVP / smoke-demo surface
- public-safe API / event / capability contracts
- approval / audit / boundary-first architecture
- provider-independent runtime direction

一方で、次はまだ完成済みとは主張していません。

- production-ready product
- official cloud complete
- live operations complete
- full product completion
- final Web product UI
- persistent cross-device memory
- full Discord product lane
- signed production release
- deployment-ready official runtime

強く見せることより、事実境界を崩さないことを優先しています。

### YonerAI の方向性

YonerAI の目的は、AI を「どのモデルを使うか」だけで終わらせないことです。

モデル、UI、実行環境、API provider が変わっても、ユーザー側の体験、操作単位、承認、監査、境界が崩れないようにすることを目指しています。

長期的には、次の 3 モードを同じ思想で扱う構想です。

| Mode | 概要 |
| --- | --- |
| Full Private Self-Host | ユーザーが runtime boundary を自分で持つ |
| Official Hybrid Private | 公式側の統治とローカル / private runtime を契約で接続する |
| Official Managed Cloud | 同じ体験を managed surface として提供する |

### Build Philosophy

- AI は便利さだけでなく、境界・承認・監査まで含めて設計する
- public と private を混ぜない
- 完成していないものを完成済みと書かない
- model provider に依存しすぎない
- ユーザーが自分の環境を失わない AI 体験を作る
- 派手な demo より、再現可能な contract とテストを重視する

---

## 🌍 English Profile

I am building **YonerAI**, a provider-independent AI runtime foundation.

The goal is not just to switch between models.  
The goal is to keep one reliable AI experience across official, local, and self-hosted environments.

YonerAI is not just a Discord bot, and not just a model router.

It is being designed around:

- provider independence
- same experience across official / local / self-host
- public / private / control-plane separation
- API / CLI / Web / Discord surface boundaries
- typed actions
- approval gates
- auditability
- local Core API
- mock / offline / loopback local LLM paths
- self-evolution as approval-gated product intelligence

### Current Public Status

The public repository is not presented as a finished product.

The current public direction is a contract-first runtime foundation with:

- local Core API smoke path
- mock / offline message contract
- loopback-only local LLM conversation path
- CLI client
- temporary Web Chat MVP / smoke-demo surface
- public-safe API / event / capability contracts
- boundary-first architecture

It does not claim production readiness, official cloud completion, live operations completion, or full product completion.

---

## Flagship Project

### [YonerAI](https://github.com/YoneRai12/YonerAI)

Provider-independent AI execution foundation for keeping one reliable AI experience across official, local, and self-hosted runtimes.

Core themes:

- local-first AI runtime
- provider-independent execution
- same-experience architecture
- contract-first API / CLI / Web surfaces
- approval / audit / capability boundaries
- public/private separation
- self-evolution with evidence, tests, approval, and rollback

---

## Interests

- AI runtime architecture
- local-first AI
- provider-independent AI systems
- AI agents / tool calling / approval gates
- CLI / Web / API product surfaces
- self-host / hybrid deployment
- security-first automation
- GitHub Actions / CI / release workflows
- practical systems that actually run

---

## Tech Stack

| Area | Main Stack |
| --- | --- |
| Languages | Python, TypeScript / JavaScript |
| AI / Runtime | LLM routing, provider abstraction, local LLM, tool calling |
| Backend | FastAPI, HTTP APIs, SSE-style contracts, runtime services |
| Frontend | Next.js, web chat, dashboard-style surfaces |
| CLI | local command UX, smoke tests, developer tools |
| Infra / Ops | GitHub Actions, Docker, Cloudflare, VPS / local runtime |
| Other | Discord bots, automation, GPU / local environment work |

---

## Selected Work

### [YonerAI](https://github.com/YoneRai12/YonerAI)

My main project.  
A provider-independent AI runtime foundation for official, local, and self-hosted AI experiences.

### Other experiments

- Minecraft and AI experiments
- Discord safety / anti-vandalism automation
- GPU / runtime / local AI debugging
- Web and automation prototypes

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
