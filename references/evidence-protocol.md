# Evidence retrieval and citation audit

## Scope the search

Identify whether the task is a provided-manuscript appraisal, targeted evidence check, scoping exercise, or formal evidence synthesis. Match the scope to the user's request and available tools. Do not relabel a targeted search as a systematic review.

For retrieval, record databases/sites, exact queries, search date, filters, and limits. Use discipline-appropriate primary databases when available; for biomedical research, consider PubMed/MEDLINE, trial registries, and relevant publisher sources. Say when only general web search or abstracts were accessible. Do not imply access to a database through a search engine.

Search concept synonyms, relevant populations, outcomes, designs, and competing explanations. Include contradictory and null findings. Identify current syntheses and trace pivotal claims to original studies. Assess a review's methods, included evidence, and search date rather than assuming it is definitive. Keep preprints, protocols, registered studies, and peer-reviewed results distinguishable. Distinguish study from report; multiple publications from one cohort are not independent replication.

Stop a targeted search when the decision-relevant claims have support or explicitly documented gaps, and report coverage limits. Record unsearched sources rather than claiming completeness. For formal reviews, require a protocol and reproducible eligibility, search, screening, extraction, and appraisal procedures; record who actually performed each step. Multiple AI passes are not independent human screening.

## Minimal evidence ledger

Maintain only fields relevant to the task; use “not reported” or “not accessed” instead of guessing.

| Field | Record |
| --- | --- |
| Claim ID | The exact proposition being assessed |
| Source ID | Stable ID and verified bibliographic details; DOI/PMID/URL when confirmed |
| Access | Full text inspected, abstract only, supplied excerpt, or unverified lead |
| Location | Page, section, table, figure, paragraph, or dataset/code location |
| Design and sample | Design, setting, population, sample/denominator, timing, comparator |
| Finding | Effect estimate, uncertainty, units, adjustments, and outcome definition as reported |
| Claim fit | Supports, qualifies, contradicts, or does not address the proposition |
| Limitations | Relevant bias, imprecision, indirectness, conflicts, and scope limits |
| Status | Retraction/correction/preprint checks performed and any remaining uncertainty |

Use the ledger to prevent citation drift between drafts. Mark conclusions derived from methodological reasoning as such; they need not pretend to be empirical findings from a paper.

## Verify citations in two stages

1. **Identity:** confirm title, author(s), year, venue, and identifier against a publisher or authoritative bibliographic record. If records conflict, inspect the version and publication history. Do not reconstruct a DOI from a title or fill in authors from memory.
2. **Support:** inspect the actual relevant passage, table, or figure. Check that the claim matches the population, comparator, endpoint, timeframe, and direction/magnitude of the result. A title or search snippet alone is not enough. With abstract-only access, restrict claims to information actually in the abstract and leave unreported methods unresolved.

For pivotal sources, check available publisher notices and bibliographic flags for corrections or retractions. Report “no notice identified in the sources checked” rather than asserting a universal negative. A corrected or retracted article may be discussed as an object of analysis but must not silently support a conclusion as valid evidence.

If retrieval fails, report the failure and proceed with bounded appraisal. Keep unverified citations out of manuscript-ready reference lists. Use `[reference needed]` only as an explicit drafting placeholder. If the user insists on an unverified citation, label it unverified rather than formatting it as confirmed evidence.

## Novelty and negative evidence

Never declare “the first study,” “no studies exist,” or “no evidence” from a limited search. Prefer “No eligible study was identified in [sources and searches] as of [date].” Separate absence of identified evidence from evidence of absence. Identify whether apparent replication uses overlapping participants, reused datasets, or closely related methods.

## Reporting guidance

Use the [EQUATOR Network](https://www.equator-network.org/) to identify the current guideline and relevant extensions for health research. Verify the actual checklist/version before claiming compliance. Use reporting guidance to identify missing reporting, and a separate appropriate tool if formal risk-of-bias appraisal is requested.

| Research type | Guideline family to check |
| --- | --- |
| Randomized trial / trial protocol | CONSORT / SPIRIT |
| Observational study | STROBE; relevant extensions for the data/design |
| Systematic review / review protocol | PRISMA / PRISMA-P; applicable extensions |
| Diagnostic accuracy / prediction model | STARD / TRIPOD; applicable AI extensions |
| Qualitative study | SRQR or COREQ, according to design |
| Animal study / case report | ARRIVE / CARE |

Do not apply every guideline, freeze an obsolete version, or infer study quality from checklist completeness. In other disciplines, identify the relevant field-specific standards.
