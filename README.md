# YoneRai12

ローカルファーストな AI システム、Discord ネイティブな AI、Node + Relay + Core のような構成を考えて作っています。

今いちばん力を入れているのは **YonerAI** です。
これは、まず自分のPCで動くことを前提にした AI システムで、単なるチャットUIではなく、

- Discord Bot
- Web UI
- Core
- Relay
- tools / skills
- approvals / audit

まで含めて組んでいます。

---

## 今やっていること

- **YonerAI の公開版 Node を整理すること**
  - ユーザーのPCで動く、配布可能な YonerAI 側を整備中
- **YonerAI の private 側を分離すること**
  - VPS、商業運用、公式Web、運用AI を分けて設計中
- **Discord / PC / operator 系の AI 体験を作ること**
  - 日常で使える AI と、実際に動く AI をつなげたい
- **ローカル実行と hybrid 構成の両立**
  - 自分のPCに住むAIと、VPSの control plane を両立できる形を考えている

---

## Flagship Project

### [YonerAI](https://github.com/YoneRai12/YonerAI)

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

## ほかの公開プロジェクト

### [Minecraft-AI-Bedrock-Edition](https://github.com/YoneRai12/Minecraft-AI-Bedrock-Edition)
Minecraft と AI の組み合わせを試しているプロジェクト。

### [RTX5090-DebugSystem](https://github.com/YoneRai12/RTX5090-DebugSystem)
GPU / 実行環境 / デバッグ系の実験用プロジェクト。

### [Discord-Measures-against-vandalism-YoneRai12](https://github.com/YoneRai12/Discord-Measures-against-vandalism-YoneRai12)
Discord サーバー向けの荒らし対策 / セキュリティ系 Bot コード。

---

## 関心のある領域

- ローカルファースト AI
- Discord ネイティブな AI 体験
- AI agent / tool calling / approval / audit
- Node + Relay + Core の分離構成
- Windows / VPS / hybrid deployment
- 実際に使われる泥臭い自動化

---

## 技術スタック

| 分野 | 主に使うもの |
| --- | --- |
| 言語 | Python, TypeScript / JavaScript |
| AI / Runtime | LLM routing, tool calling, MCP, local-first AI |
| Backend | FastAPI, WebSocket, relay patterns |
| Frontend | Next.js, dashboard / web UI |
| Infra / Ops | GitHub Actions, VPS, Cloudflare, deployment flows |
| その他 | Discord bots, automation, GPU / local runtime 周り |

---

## 作り方の方針

- まず自分で使いたいものを作る
- ただのラッパーではなく、システムとして骨格から考える
- public と private の境界を意識する
- 実際に動くものを優先する
- 後から派生できる土台を残す

---

## Links

- GitHub: [YoneRai12](https://github.com/YoneRai12)
- YonerAI: [github.com/YoneRai12/YonerAI](https://github.com/YoneRai12/YonerAI)
- Mail: [hello@yonerai.com](mailto:hello@yonerai.com)
- Qiita: [qiita.com/YoneRai12](https://qiita.com/YoneRai12)
- X: [x.com/YoneRai12](https://x.com/YoneRai12)

---

[![GitHub Streak](https://streak-stats.demolab.com/?user=YoneRai12&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)
