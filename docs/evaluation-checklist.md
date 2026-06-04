# AI librarian evaluation checklist

Use this checklist before and during an AI librarian pilot. Mark each item as `Not started`, `In progress`, `Passed`, `Accepted risk`, or `Blocked`.

## Governance

- [ ] Service owner and backup owner are named.
- [ ] Approved use cases and prohibited use cases are documented.
- [ ] Public AI disclosure language is drafted.
- [ ] Staff escalation and takedown process is documented.
- [ ] Vendor, model, and data-processing terms are reviewed.

## Knowledge and retrieval quality

- [ ] Every answer type maps to approved sources.
- [ ] Retrieval excludes private, restricted, obsolete, and unlicensed material.
- [ ] Answers cite sources or clearly say when no source was found.
- [ ] The assistant distinguishes catalog/database discovery from full-text access.
- [ ] Known coverage gaps are documented for staff and patrons.

## Reference quality

- [ ] Benchmark questions include directional, policy, database, citation, and research-strategy prompts.
- [ ] Staff reviewers score accuracy, helpfulness, completeness, tone, and citation quality.
- [ ] The assistant asks clarifying questions when patron intent is ambiguous.
- [ ] The assistant avoids inventing titles, citations, call numbers, databases, policies, or staff names.
- [ ] The assistant recommends human help for complex or sensitive questions.

## Privacy and security

- [ ] Data minimization is implemented.
- [ ] Sensitive-data warnings are visible before free-text entry.
- [ ] Chat logs and analytics follow retention requirements.
- [ ] Authentication, if used, is justified and documented.
- [ ] Incident response includes model/vendor outages and data-exposure scenarios.

## Equity and accessibility

- [ ] Interface meets the local accessibility target.
- [ ] Plain-language responses are available.
- [ ] Multilingual behavior is tested for supported languages.
- [ ] Recommendations do not systematically privilege only the most popular, expensive, or English-language resources.
- [ ] Patron feedback channels are accessible and monitored.

## Launch gates

A public pilot should not proceed unless:

1. Critical hallucination defects are fixed or mitigated.
2. Staff can reproduce source citations used in benchmark answers.
3. A human handoff is available from every high-risk answer path.
4. Patron-facing disclosures are approved.
5. Monitoring, review cadence, and rollback authority are assigned.
