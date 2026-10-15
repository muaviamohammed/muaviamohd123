# Muavia Mohammed

**Founder & CEO, [MIZAN](https://mizan.market)**: the proof layer for AI trading agents.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muaviamohammed) [![X](https://img.shields.io/badge/X-000000?logo=x&logoColor=white)](https://x.com/mohd_muavia) [![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/muaviamohammed) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:muavia@mizan.market)

---

### What I'm building

AI agents are starting to manage money, and none of them can prove their record. Backtests are cheap to fake and easy to overfit, and no builder with a real edge will show their strategy.

**MIZAN proves an agent's track record without revealing the agent.** Its trades are scored on fixed, public market data, after costs, under a published test (return, drawdown, risk-adjusted performance, out-of-sample results), entirely inside a **RISC Zero zkVM**. The result is a **~220 KB STARK proof** that anyone can verify in milliseconds, offline, for free, without asking us.

**Prove the edge. Never reveal it.**

```
Engine                 LIVE · era v12 · RISC Zero zkVM · STARK
Written                18,000+ lines of Rust, solo, before raising
Markets                668 canonical: crypto, US ETFs, US stocks
                       every series pinned by a published Merkle root
Proof                  ~220 KB STARK receipt
Verify                 milliseconds · free · offline · permissionless
Verifier               macOS · Linux · Windows (one-bit tamper → refused)
Anchoring              RFC-3161 timestamp + Bitcoin (OpenTimestamps)
Public registry        85 credentials · 58 refused · published anyway
Standard               VTR-1, the open Verifiable Track Record standard
For agents             MCP server · A2A endpoint · Python SDK
Self-serve             studio.mizan.market/app (1–8 markets per book)
```

### Why this exists

Bonds have ratings. Companies have audits. Asset managers have performance standards. AI trading agents have a screenshot.

An agent can't be interviewed. It can test a thousand strategies in an hour and show you the best one. And it will never show its code, because the strategy is the whole business. So capital is stuck choosing between trusting the claim and demanding the code.

**MIZAN is the third choice: proof instead of disclosure.**

### The discipline

I learned this problem the hard way. I built my own quant research system, and it found backtests with Sharpe ratios above 10. I put real money on one: the backtest said it won almost every trade; live, it lost 7 of its first 8. The "edge" was a bug.

So I audited everything I'd built and **retracted 40+ of my own strategies, with the root cause published on each**. Then I built the referee that would have caught them, and pointed it at my own work first.

It refused most of it, including one of my own AI agents at **+895%**. That refusal is [public](https://studio.mizan.market/credential/zkml11-verifiable-ai-nvda).

**A proof system that only shows winners is marketing. Trust comes from what it refuses.**

### Now

🟢 Engine live (era v12) · self-serve minting open · integrations in review with Coinbase AgentKit, GOAT SDK, CrewAI and the Docker MCP registry · raising a seed round

**Next:** live forward tracks, where every decision is committed before the market moves, and agents that mint with no human in the loop.

---

### Find me

- 🌐 [mizan.market](https://mizan.market) · [Verify a credential](https://mizan.market/verify/) · [Registry](https://mizan.market/registry/) · [VTR-1 standard](https://mizan.market/standard/)
- 🧪 [Prove your agent](https://studio.mizan.market/app/) · [mizan-mcp](https://github.com/muaviamohammed/mizan-mcp) · [mizan-verify](https://github.com/muaviamohammed/mizan-verify)
- 💼 [Investors](https://mizan.market/investors/) · deck and data room on request
- ✉️ muavia@mizan.market

---

<sub>Most backtests are fake. We prove the few that aren't, without ever seeing them.</sub>
