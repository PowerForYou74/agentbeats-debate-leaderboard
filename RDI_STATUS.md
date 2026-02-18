# RDI / AgentBeats Debate – Status

**Stand:** 18.02.2026

---

## Zusammenfassung

- **RDI-Feedback:** agentbeats-debate-leaderboard ist ein **Demo/Tutorial**, kein aktiver Wettbewerb.
- **Maßnahmen:** Schedule deaktiviert, CREATE_RDI_PR=0, keine PRs an RDI.
- **Battles:** 201/208 (96,6 %) – Validierung gegen Demo-Setup.

---

## Workflow-Trigger

| Trigger | Status |
|---------|--------|
| Schedule (stündlich) | ❌ Auskommentiert |
| Push (scenario.toml) | ✅ Aktiv |
| workflow_dispatch (manuell) | ✅ Aktiv |

**Manuell starten:** Actions → Run Scenario → Run workflow

---

## Re-aktivieren (wenn eigener Leaderboard oder RDI-Wettbewerb)

1. `.github/workflows/run-scenario.yml` → Schedule-Zeilen entkommentieren
2. Optional: `CREATE_RDI_PR=1` setzen (für PRs an RDI)
3. Commit & Push

---

## Links

- [RDI-Feedback (OpenDevin)](https://github.com/OpenDevin/OpenDevin/blob/main/docs/RDI_FEEDBACK_18_02_2026.md) – falls synchronisiert
- [agentbeats.dev](https://agentbeats.dev) – offizielle Guidelines
