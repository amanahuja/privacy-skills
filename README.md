# privacy-skills

A collection of agent skills for privacy policy analysis.

## Skills

### privacy-policy-reviewer

Review a privacy policy or terms of service against a structured scorecard.
Combines ToS;DR's human-curated ratings with LLM analysis. Use it next time
instead of just clicking "Accept"! 

**Features:**
- ToS;DR API lookup — surfaces existing human-curated ratings and "Points"
- Summary scorecard covering cookies, data collection, advertising and more.
- Hybrid output: ToS;DR-verified findings clearly distinguished from
  LLM-generated analysis
- Jurisdiction-aware narrative (US, EU/GDPR, US state-specific)
- Direct policy quotes for every finding

**Supports different Multiple Privacy Review options:**
- Our privacy concerns depend on context and the type of service.
- Methodology to support reviews based on the users's threat model, level
of privacy concern, or type of application. 
- There are three reviews currently written into the skill: 
    - Standard, Enhanced, and High Sensitivity
- create your own on the fly if none of them fit. 


**Install:**
```
npx skills add amanahuja/privacy-skills@privacy-policy-reviewer
```

**Trigger examples:**
- "Review the privacy policy at [URL]"
- "Analyze the terms of service for [service name]"
- "What am I agreeing to if I sign up for [service]?"

**Resources used:**
- [ToS;DR](https://tosdr.org) — Terms of Service; Didn't Read
- [ToS;DR API](https://docs.tosdr.org/developer)
- [Open Terms Archive](https://opentermsarchive.org)

---

## Future / Planned Skills

- **privacy-policy-diff** — Compare two versions of a privacy policy and
  surface what changed, whether changes are better or worse for users, and
  what requires immediate action.

---

## Contributing

Issues and pull requests welcome. To suggest a new skill or report an
inaccuracy in the ToS;DR taxonomy mapping, open an issue.
