# Reinforcement-Learning Agent Codex Instructions

Before planning, answering, or changing files:

1. Read `governance/MASTER_PROJECT_CONTEXT.md` completely.
2. Read `governance/CURRENT_STATUS.md` and `governance/INTEGRATION_VERSIONS.yaml`.
3. Read this repository's `README.md`.
4. Verify the pinned submodule with `git submodule status governance`.
5. Report the verification block below at the beginning of a new Codex chat.

```text
Governance verification:
- Governance commit:
- System version:
- Component: Reinforcement-Learning Agent
- Delivery phase: Phase 6
- Relevant acceptance gate: Across seeds and regimes, the agent beats declared non-RL baselines after adverse costs without prohibited tail risk.
```

Stop if `governance/MASTER_PROJECT_CONTEXT.md` is missing or unreadable. The agent must use the shared simulator and remain subject to risk-engine vetoes. Do not introduce RL before deterministic baselines and risk controls are validated.

