## Konstantin Baltsat

I build RL environments for frontier models and agents that take over real company processes. Remote, any timezone.

### What I build

**RL environments and graders.** Tasks mined from frontier-model failure modes, hidden scorers, replayable judge traces, reward-hacking checks. Plus the data infra behind them: distributed scraping workers, cross-region code corpora, dedup and quality filters.

**Agents for business processes.** A company brain that pulls finance, sales and ops data from 40+ connectors into one versioned store with access control. Consultant agents where every write waits for a human approval and numbers come only from verified tools. Every incoming stream (chats, calls, docs) digitized, every human decision point logged, and the recurring ones handed to agents. MCP servers, multi-agent swarms, agent memory.

**ML in production.** Recommenders shipped to 40M+ users, LLM moderation and retrieval pipelines, robot recovery loops, checkpoint-to-service delivery cut from 6h to 5m.

### Research

[*HL-EAI: A Multimodal Framework Enabling Emotional Reciprocity in Human–AI Strategic Decision-Making*](https://dl.acm.org/doi/10.1145/3746027.3754468). Mozikov, Orekhov, Nasonov, Baltsat, et al., ACM Multimedia 2025. LLM agents and humans in dictator-game, GTBench and trolley-dilemma settings: how emotional cues change agent decisions, trust and cooperation.

### Merged open-source contributions

Small, sharp fixes in other people's codebases, mostly parser, formatter and SDK correctness bugs.

| Project | Contribution |
| --- | --- |
| [highlight.js](https://github.com/highlightjs/highlight.js) ★24k | [#4455](https://github.com/highlightjs/highlight.js/pull/4455) qualified generic type arguments in Java · [#4453](https://github.com/highlightjs/highlight.js/pull/4453) `where` in Haskell GADT declarations · [#4454](https://github.com/highlightjs/highlight.js/pull/4454) six-digit unicode ranges in CSS |
| [pest](https://github.com/pest-parser/pest) ★4.8k | [#1184](https://github.com/pest-parser/pest/pull/1184) restore stack state after a failed sequence |
| [agntcy/dir](https://github.com/agntcy/dir) | [#1892](https://github.com/agntcy/dir/pull/1892) register cloud KMS providers · [#1891](https://github.com/agntcy/dir/pull/1891) avoid blocking on non-interactive key passwords · [#1890](https://github.com/agntcy/dir/pull/1890) synchronize in-memory routing datastore |
| [OpenFeature flagd](https://github.com/open-feature/flagd) (CNCF) | [#2006](https://github.com/open-feature/flagd/pull/2006) synchronize readiness state |
| [OpenFeature go-sdk-contrib](https://github.com/open-feature/go-sdk-contrib) (CNCF) | [#927](https://github.com/open-feature/go-sdk-contrib/pull/927) safely compare complex criteria values |

Open and under review: [undici #5601](https://github.com/nodejs/undici/pull/5601) (reject SharedArrayBuffer-backed body views), [oxc #25022](https://github.com/oxc-project/oxc/pull/25022), [pygments #3234](https://github.com/pygments/pygments/pull/3234).

BSc in Applied Computer Science, ITMO – Best Graduate 2024 · Python, C++, PyTorch, JAX, MCP, Terraform
