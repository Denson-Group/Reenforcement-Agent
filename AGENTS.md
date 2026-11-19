# Reinforcement-Learning Agent Codex Instructions

Before planning, answering, or changing files:

1. Read `governance/MASTER_PROJECT_CONTEXT.md` completely.
2. Read `governance/DELTA_NEUTRAL_HEDGING_SPEC.md` completely.
3. Read `governance/CURRENT_STATUS.md` and `governance/INTEGRATION_VERSIONS.yaml`.
4. Read this repository's `README.md`.
5. Verify the pinned submodule with `git submodule status governance`.
6. Report the verification block below at the beginning of a new Codex chat.

```text
Governance verification:
- Governance commit:
- System version:
- Component: Reinforcement-Learning Agent
- Delivery phase: Phase 6
- Relevant acceptance gate: Across seeds and regimes, the agent beats declared non-RL baselines after adverse costs without prohibited tail risk.
```

Stop if `governance/MASTER_PROJECT_CONTEXT.md` is missing or unreadable. The agent must use the shared simulator and remain subject to risk-engine vetoes. Do not introduce RL before deterministic baselines and risk controls are validated.

Observations may include point-in-time Market Data Engine features and versioned Prediction Models forecasts. Actions may select only legal open/hold/hedge/close choices. Do not recalculate data with future information, redefine Greeks or P&L, embed a private fill model, or bypass costs and risk controls enforced by the environment.

