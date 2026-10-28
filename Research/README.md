# 🔬 CEI Research Archive

> A source-traceable record of cyber incidents and the evidence needed to study how cyberspace changes.

[← Project overview](../README.md) · [Research methodology](../Docs/Research_Methodology.md) · [AI architecture](../Docs/AI_Architecture.md) · [Roadmap](../ROADMAP.md)

---

## Browse the archive

| Collection | Contents | Current state |
|---|---|---|
| [1980s](./1980s/) | Early computing and security history | Collection scaffold |
| [1990s](./1990s/) | Historical incidents, including the Melissa virus | Initial case study present |
| [2000s](./2000s/) | Incidents and shifts in the cyber landscape | Collection scaffold |
| [2010s](./2010s/) | Modern exploit, malware, and campaign history | Collection scaffold |
| [2020s](./2020s/) | Contemporary incidents and vulnerability research | Case studies present |
| [Vulnerabilities](./Vulnerabilities/) | Vulnerability-focused research | Collection scaffold |
| [Malware](./Malware/) | Malware families and behavioral change | Collection scaffold |
| [Threat actors](./Threat_Actors/) | Publicly documented actors and campaigns | Collection scaffold |
| [Defensive technologies](./Defensive_Technologies/) | Detection, mitigation, and defensive adaptation | Collection scaffold |
| [Artificial intelligence](./Artificial_Intelligence/) | AI-related security and AI-assisted research | Collection scaffold |
| [Papers](./Papers/) | Research papers and technical literature | Collection scaffold |
| [Timelines](./Timelines/) | Chronological views across incidents | Timeline documents present |

“Collection scaffold” means the category exists but should not be interpreted as a complete or populated dataset.

## Featured research

- [Melissa virus (1999)](./1990s/Melissa%20Virus%20(1999).md) — A historical malware case study.
- [PHP2Shell vulnerability research](./2020s/CEI-2026-1021-01-PHP2Shell.md) — Contemporary vulnerability-focused research.
- [OpenAI–Hugging Face security incident (2026)](./2020s/OpenAI%E2%80%93Hugging%20Face%20Security%20Incident%20(2026).md) — Incident analysis.
- [OpenAI–Hugging Face incident timeline](./Timelines/OpenAI-Hugging-Face-Incident-2026.md) — Timeline view.

These documents are research records, not automatically verified ground truth. Check each report's sources, dates, scope, and uncertainty before using it in analysis.

## What a strong record contains

Where the evidence is available, an incident record should capture:

- A stable incident identifier and clear title
- Event dates and source publication dates
- A concise summary and scope of impact
- A timeline with citations
- Relevant vulnerabilities, techniques, malware, and affected systems
- Detection, response, and defensive changes
- Primary sources and corroborating reporting
- What remains unknown or disputed
- Lessons learned and links to related records

Use the [Incident Record Template](../Docs/Templates/Incident_Record.md) as a starting point. Missing information should be labelled unknown—not guessed.

## Evidence standards

**Source every material claim.** Prefer primary advisories, incident statements, technical reports, CVE records, papers, and official disclosures where available. Use secondary reporting to add context or corroboration, and clearly identify it as such.

For every source, record enough information to assess provenance: title, publisher, URL, publication date, access date when useful, and which claim it supports. If sources conflict, preserve the disagreement instead of silently choosing the most convenient version.

## From archive to research

The archive is the foundation, not the finished system:

1. Collect and review evidence.
2. Normalize records and preserve provenance.
3. Link related incidents, techniques, vulnerabilities, and defenses.
4. Define hypotheses that could be wrong.
5. Evaluate against historical baselines and chronological holdouts.
6. Keep the forecast and its later assessment auditable.

See [Forecast Evaluation](../Docs/Forecast_Evaluation.md) for evaluation principles. The project does not claim a production forecasting pipeline exists until its implementation and results are available for inspection.
