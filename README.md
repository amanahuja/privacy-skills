# privacy-skills

A collection of agent skills for privacy policy analysis.

## Skills

### privacy-policy-reviewer

Review a privacy policy or terms of service against a structured 12-row
scorecard. Combines TOSDR's human-curated ratings with LLM analysis.
Designed for privacy-conscious users who want a fast, honest, sourced read
of what they are actually agreeing to.

**Features:**
- TOSDR API lookup — surfaces existing human-curated ratings and points
- 12-row scorecard covering cookies, data collection, advertising, your
  rights, content ownership, retention, terms changes, suspension,
  arbitration, acquisition, and government requests
- Three review tiers: Standard, Enhanced, High Sensitivity
- Hybrid output: TOSDR-verified findings clearly distinguished from
  LLM-generated analysis
- Jurisdiction-aware narrative (US, EU/GDPR, US state-specific)
- Direct policy quotes for every finding

**Install:**
```
npx skills add amanahuja/privacy-skills@privacy-policy-reviewer
```

**Trigger examples:**
- "Review the privacy policy at [URL]"
- "Analyze the terms of service for [service name]"
- "What am I agreeing to if I sign up for [service]?"

**Resources used:**
- [TOSDR](https://tosdr.org) — Terms of Service; Didn't Read
- [TOSDR API](https://docs.tosdr.org/developer)
- [Open Terms Archive](https://opentermsarchive.org)

---

## Planned Skills

- **privacy-policy-diff** — Compare two versions of a privacy policy and
  surface what changed, whether changes are better or worse for users, and
  what requires immediate action.

---

## Contributing

Issues and pull requests welcome. To suggest a new skill or report an
inaccuracy in the TOSDR taxonomy mapping, open an issue.
