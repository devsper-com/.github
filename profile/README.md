<!-- Profile readme for devsper-com -->
<p align="center">
  <img src="https://github.com/devsper-com.png" alt="devsper" width="120" style="border-radius: 50%;" />
</p>

<h1 align="center">devsper</h1>

<p align="center">
  Distributed AI swarm runtime for complex developer tasks.
</p>

<p align="center">
  <a href="https://devsper.com">devsper.com</a> ·
  <a href="https://docs.devsper.com">docs</a> ·
  <a href="https://registry.devsper.com">registry</a>
</p>

---

**devsper** turns any task into a DAG of specialized AI agents — planning, executing, and synthesizing in parallel. Built for developers who need more than a chatbot.
```bash
pip install devsper
devsper run "Research the top AI papers this week and draft a newsletter"
```
```
⣾ Planning... spawning 5 agents
✓ research_agent    found 847 papers          2.1s
✓ filter_agent      shortlisted top 5         1.8s
✓ summarizer_1      GPT-4o summaries done     3.2s
✓ summarizer_2      Claude summaries done     2.9s
✓ writer_agent      newsletter.md written     4.1s

Complete in 12.4s · $0.08 · 5 agents
```

---

### repos

| repo | description |
|------|-------------|
| [devsper-com/runtime](https://github.com/devsper-com/runtime) | Python runtime + Rust worker — the OSS core |
| [devsper-com/registry](https://github.com/devsper-com/registry) | Plugin registry — PyPI-compatible, self-hostable |
| [devsper-com/platform](https://github.com/devsper-com/platform) | Hosted platform — managed swarms, projects, nodes |

---

### what's inside

- **DAG execution** — tasks run in parallel where possible, in order where required
- **Persistent memory** — agents remember across runs, vector search over past context
- **Plugin ecosystem** — extend with tools from the registry or build your own
- **Self-healing** — failed tasks are diagnosed and retried with a different strategy
- **Distributed** — scale across nodes with the Rust worker and Redis bus
- **Run intelligence** — cost tracking, critical path analysis, bottleneck detection

---

<p align="center">
  <a href="https://docs.devsper.com/getting-started/quickstart">quickstart</a> ·
  <a href="https://docs.devsper.com/plugins/publishing">publish a plugin</a> ·
  <a href="https://registry.devsper.com">browse the registry</a>
</p>
