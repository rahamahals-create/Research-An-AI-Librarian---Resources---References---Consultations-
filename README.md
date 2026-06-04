# AI-LibrariansGPT

A practical starter kit for building, evaluating, and consulting on an **AI librarian** assistant: a retrieval-grounded GPT-style service that helps patrons discover library resources while preserving librarian values such as privacy, intellectual freedom, accessibility, citation quality, and human accountability.

> Repository focus: research resources, reference workflows, consultation templates, and governance checklists for library teams exploring AI-assisted reference services.

## What this repository provides

- A concise implementation roadmap for an AI librarian assistant.
- A curated resource list with current library, education, and AI-risk references.
- Consultation questions for stakeholders, vendors, librarians, and patrons.
- A safety and quality checklist that can be reused during pilots.
- Starter prompt patterns for reference, readers' advisory, and research-support use cases.

## Suggested AI librarian scope

An AI librarian should be designed as a **decision-support and discovery tool**, not as a replacement for professional librarians. Recommended initial capabilities include:

1. Answer directional and policy questions using library-approved content.
2. Recommend databases, subject guides, catalog searches, and librarian contact paths.
3. Explain search strategies and citation workflows.
4. Flag uncertainty, missing evidence, restricted content, and cases needing staff handoff.
5. Preserve patron privacy by minimizing data collection and avoiding unnecessary retention.

Out-of-scope functions for early pilots should include legal, medical, financial, immigration, crisis, and disciplinary decisions unless a library has a reviewed policy, qualified staff oversight, and jurisdiction-specific escalation procedures.

## Repository structure

```text
.
├── README.md
├── docs/
│   ├── consultation-guide.md
│   ├── evaluation-checklist.md
│   └── resources.md
├── prompts/
│   └── ai-librarian-system-prompt.md
├── site/
│   ├── index.html
│   └── styles.css
└── docs/website-setup.md
```

## Quick-start pilot plan

| Phase | Goal | Outputs |
| --- | --- | --- |
| 1. Discovery | Identify patron needs, staff pain points, approved sources, and risk tolerance. | Consultation notes, use-case inventory, data-flow sketch. |
| 2. Knowledge design | Select authoritative sources and decide what should never be indexed. | Source register, update cadence, exclusion list. |
| 3. Prototype | Build a retrieval-grounded assistant for a narrow service area. | Test bot, prompt pack, staff review queue. |
| 4. Evaluation | Measure answer quality, citation accuracy, accessibility, privacy, and handoff behavior. | Evaluation report, defect log, go/no-go decision. |
| 5. Governance | Assign ownership for updates, monitoring, incident response, and patron notices. | Governance charter, review calendar, public disclosure language. |

## Principles for AI library services

- **Human-centered service:** make staff escalation easy and visible.
- **Evidence-first answers:** cite library-approved sources and explain when information is uncertain.
- **Privacy by design:** collect the least patron data needed to provide the service.
- **Equitable access:** test for accessibility, multilingual support, and bias in recommendations.
- **Transparency:** disclose AI use, limitations, source coverage, and data practices.
- **Continuous review:** treat the assistant as a maintained service, not a one-time launch.

## Key references

See [`docs/resources.md`](docs/resources.md) for a curated list. Foundational references include:

- ACRL, **AI Competencies for Academic Library Workers**.
- IFLA, **Statement on Libraries and Artificial Intelligence**.
- NIST, **AI Risk Management Framework** and **Generative AI Profile**.
- UNESCO, **AI competency frameworks** for education.

## Recommended next steps

1. Customize the consultation guide for your library type and jurisdiction.
2. Fill out the evaluation checklist before selecting vendors or models.
3. Draft a public patron-facing AI notice and internal staff escalation policy.
4. Run a small staff-only pilot before exposing the assistant to patrons.
5. Record all assumptions, approved sources, and known limitations in a service register.

## License

Add a license before public reuse. For open educational/library resources, consider a Creative Commons license for documentation and an OSI-approved license for code if software is added later.


## Publish as a website

A static website starter is included in `site/`. Follow [`docs/website-setup.md`](docs/website-setup.md) to preview locally and publish with GitHub Pages.


Project Pages URL format: `https://<github-username>.github.io/<repository-name>/` (example: `https://rahamahals-create.github.io/AI-LibrariansGPT/`).
