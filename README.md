# UA agent spec

Instruction files for an AI agent that monitors and manages paid user acquisition
(Meta, Google, TikTok, DSPs; measured through AppsFlyer).

- [CLAUDE.md](CLAUDE.md) — root rules for live ad accounts, source-of-truth map,
  decision rules, read vs. act, and what every write must record.
- [agent/system-prompt.md](agent/system-prompt.md) — the agent's operating spec:
  account configuration contract, metric definitions, recommendation engine,
  forecasting and report format.

**Status:** a specification, not a running agent. Account configs, playbooks and
change logs referenced in CLAUDE.md are private; their structure is defined in §2 of
the system prompt. All names and figures are anonymized.
