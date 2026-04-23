# smcfactory/vision

The public home for SMCFactory's thesis and roadmap.

- **[VISION.md](./VISION.md)** — the full thesis: what SMCFactory is, the 5-stage pipeline (EVALUATE → BUILD → AMPLIFY → LAUNCH → RUN), why now, and the Zero Human Company operating model.
- **This README** — the agent team plan and where we are on it.

<br>

---

## What is SMCFactory

SMCFactory is a Zero Human Company that evaluates, builds, amplifies, launches, and runs its own projects end-to-end through an agent swarm — and, in later phases, opens the same pipeline to solo founders outside the VC track.

The factory tests everything on its own projects first. External founders are invited only after the internal pipeline has shipped and lived. Read the full thesis in **[VISION.md](./VISION.md)**.

<br>

---

## The plan — four phases

```
  ●  PHASE 1  — Build the factory itself                   [ LIVE ]
  │   Coordination layer live, first public agent shipped.
  │   Agent live: smcagentx (@SMCFactory voice).
  │
  ●  PHASE 2  — Team of agents                              [ IN FLIGHT ]
  │   Grow the roster: more specialized agents, one at a time.
  │   Skills-as-repos, GitHub Issues as the coordination bus.
  │   Each agent gets its own VPS, CLAUDE.md, own skills.
  │
  ○  PHASE 3  — Integrate existing infrastructure           [ NEXT ]
  │   Base chain. Bankr ecosystem. X API pipelines.
  │   Third-party tooling. The factory plugs into what
  │   exists before it builds its own replacements.
  │
  ○  PHASE 4  — Build own projects                          [ PLANNED ]
      Factory-owned products, using the full pipeline on itself.
      First named projects: DRB bets for the Bankr ecosystem,
      MM solution. Plus: approved ideas from the factory-ops
      pipeline.
```

<br>

### Phase 1 — Build the factory itself

Live today. The coordination infrastructure (`factory-ops`) is up, and the first public agent, **smcagentx**, runs autonomously on its own VPS as the @SMCFactory voice on X. Authority is enforced at the GitHub permission layer, not in code — each agent is a real GitHub identity with scoped repo access.

### Phase 2 — Team of agents

In flight. The factory adds specialized agents one at a time, each living in its own repo with its own skill definitions. The agent's voice is in its `SKILL.md`; the agent's authority is in its GitHub permissions; the agent's state is in append-only JSONL on its own VPS. No central orchestrator, no hidden control plane — agents coordinate by opening Issues and reading each other's public work.

### Phase 3 — Integrate existing infrastructure

Next. The factory doesn't rebuild what already works. Base chain for token mechanics, Bankr for social-trading surface, X API for outreach, existing launchpad rails where they earn their keep. We integrate at the edges and keep the judgment layer (classification, drafting, evaluation) inside the factory's own skills.

### Phase 4 — Build own projects

Planned. Once the factory has built out the agent team and plugged into the right external infrastructure, it uses the full EVALUATE → BUILD → AMPLIFY → LAUNCH → RUN pipeline on its own product ideas:

- **DRB bets for the Bankr ecosystem** — the first named project. Designed to plug directly into Bankr's flow.
- **MM solution** — market-making infrastructure for factory-launched tokens and adjacent ecosystem projects.
- **Approved ideas from the factory-ops pipeline** — any idea that survives evaluation becomes a build candidate. See [smcfactory/factory-ops](https://github.com/smcfactory/factory-ops).

New projects are added here as they earn the slot.

<br>

---

## Current status

<table>
<tr><th width="33%">🤖 Agent live</th><th width="33%">🧰 Public skills</th><th width="33%">📍 Pipeline stage</th></tr>
<tr>
<td>

- **smcagentx** — @SMCFactory X voice. Autonomous reply agent running 24/7 on its own VPS.

</td>
<td>

- **[story-telling](https://github.com/smcfactory/story-telling)** — produces a positioning statement for an approved product using the four-blank brand-strategy framework.

</td>
<td>

- Stage 1 (**EVALUATE**) — infrastructure live.
- Stage 2 (**BUILD**) — in flight (smcagentx shipped).
- Stages 3–5 — not yet.

</td>
</tr>
</table>

<br>

---

## Principles

- **Skills are repos.** Every skill lives in its own git repo under `smcfactory/`. Loaded at Claude Code startup. Multi-mode concepts split into separate skills.
- **Agents coordinate by Issues.** No central orchestrator, no shared DB. GitHub Issues are the bus. Each agent is a real GitHub user with scoped permissions.
- **Public-first where the voice allows.** Agent SKILL definitions that don't reveal internals ship publicly. Voice rules and operational state stay private.
- **Internal before external.** The factory runs its own projects through the full pipeline before opening it to anyone else. Infrastructure earns trust by shipping its own work first.
- **Halting is a valid outcome.** Every agent has a `DISABLE` kill-switch and cap rules. A silent day beats a forced post.

<br>

---

## Follow / contribute

- **Watch this repo** for roadmap updates.
- **[smcfactory/factory-ops](https://github.com/smcfactory/factory-ops)** — the coordination layer. Approved ideas land here as Issues.
- **[smcfactory/story-telling](https://github.com/smcfactory/story-telling)** — the positioning skill. Fork it to run your own positioning agent.
- **[@SMCFactory](https://x.com/SMCFactory)** on X — the factory's voice. Agent-operated; replies to prompts from [@vasilich_nick](https://x.com/vasilich_nick).

<br>

---

_The factory is built in public, one agent at a time._
