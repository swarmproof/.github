<h1 align="center">Swarm Proof</h1>
<p align="center"><strong>Trust infrastructure for the agent economy.</strong></p>
<p align="center"><em>Software is increasingly consumed by agents, not humans. Swarm Proof builds the open-source tooling that makes that safe — before real agents (and real money) arrive.</em></p>

---

## The toolkit

Seven projects, one thesis: *what happens when autonomous agents meet real systems and real money — and how do we make it safe?* Each earns its place alone; together they're one agent-reliability stack.

| Project | What it does |
|---------|--------------|
| 🐎 [**stampede**](https://github.com/swarmproof/stampede) | The wind tunnel for the agent economy — point a herd of realistic (and adversarial) agents at your system before real ones arrive |
| 🌍 [**mockworld**](https://github.com/swarmproof/mockworld) | A synthetic internet for agents — fake Stripe, Gmail, exchange, and more as instant MCP servers |
| 🔬 [**mcp-probe**](https://github.com/swarmproof/mcp-probe) | The CI quality suite for MCP servers — lint, contract-test, benchmark, load-test before you ship |
| 💸 [**costbomb**](https://github.com/swarmproof/costbomb) | Denial-of-wallet fuzzing — find the inputs that make your agent spend $500 to answer a $0.05 question |
| 🎯 [**exactly-once**](https://github.com/swarmproof/exactly-once) | Idempotency middleware so agent side-effects — payments, emails, onchain txs — fire exactly once |
| 📓 [**agent-postmortems**](https://github.com/swarmproof/agent-postmortems) | A structured incident database + post-mortem standard for real agent failures in the wild |
| 🗺️ [**awesome-agent-reliability**](https://github.com/swarmproof/awesome-agent-reliability) | The curated map of the field |

Applied case study: [**cairn-protocol**](https://github.com/swarmproof/cairn-protocol) — state-recovery for agents, the first system these tools are proven against.

## Where to start

- **Building an MCP server?** → [mcp-probe](https://github.com/swarmproof/mcp-probe) scores it before you publish.
- **Agents that move money?** → drop in [exactly-once](https://github.com/swarmproof/exactly-once) and fuzz with [costbomb](https://github.com/swarmproof/costbomb).
- **Shipping anything agent-facing?** → run [stampede](https://github.com/swarmproof/stampede) against it and read the Agent Readiness Report.
- **Just mapping the space?** → start at [awesome-agent-reliability](https://github.com/swarmproof/awesome-agent-reliability).

## Principles

**Provider-agnostic** (any OpenAI-compatible endpoint + Anthropic SDK, local-model friendly) · **honest over impressive** (we document the boundaries of our guarantees) · **watchable & reproducible** (seedable runs, screenshot-worthy reports) · **Apache-2.0** everywhere.

<p align="center"><sub>Contributions welcome — every repo ships with seeded <code>good-first-issue</code>s.</sub></p>
