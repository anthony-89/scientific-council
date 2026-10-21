# Conditional methodological checks

Use this as a menu, not a universal list of required analyses. Explain why a selected check affects the user's inference.

## Design, measurement, and causality

- Identify the target estimand and unit of analysis. Check eligibility, sampling, measurement validity, selection, comparator, and temporality.
- In observational work, assess confounding, reverse causation, collider bias, and inappropriate adjustment for mediators or post-exposure variables. Do not equate multivariable adjustment or propensity methods with removal of all confounding.
- In trials, inspect randomization, allocation concealment, blinding where feasible, adherence, attrition, estimand, analysis population, and prespecified outcomes. Do not assume these occurred merely because the report says “randomized.”
- For causal analyses, state the identification assumptions and which are untestable from the observed data. Consider an explicit causal diagram if it clarifies covariate selection.
- For uncontrolled pre/post studies, consider secular change, maturation, regression to the mean, repeat testing, response shift, selection, and attrition. A within-person improvement does not by itself identify the intervention effect.
- In education research, distinguish self-rated confidence, tested knowledge, demonstrated competence, behavior change, and downstream outcomes. Check instrument validity, scoring, retention, and setting-specific transfer.
- Distinguish missing methodological reporting from a confirmed design defect.

## Statistical inference

- Verify sample sizes, events, denominators, repeated measures, clustering, paired structure, and analytical units; avoid pseudoreplication.
- Report effect estimates and uncertainty in units relevant to the question. Distinguish statistical significance, clinical/practical importance, equivalence, and absence of evidence.
- Interpret intervals in context; do not call a frequentist confidence interval a posterior probability. A nonsignificant comparison does not establish equivalence without a suitable design and justified margins.
- Check primary versus exploratory endpoints, multiple testing, subgroup interaction tests, multiplicity control, model assumptions, diagnostics, and sensitivity analyses. Do not infer subgroup differences from significance in one group and nonsignificance in another.
- Assess missingness patterns, plausible mechanisms, handling, and sensitivity to assumptions. Do not recommend imputation automatically or treat complete-case analysis as universally invalid.
- Base prospective sample-size planning on the design, target effect/precision, variability or event assumptions, and plausible attrition. Do not use observed post-hoc power to explain a null result.
- Do not compute unreported standard errors, paired-change uncertainty, or sample-size requirements without the necessary inputs. If demonstrating an assumption-based calculation, label inputs and output as illustrative.
- Report which calculations ran, with code or enough formulas/inputs to reproduce them when requested. Never claim to have inspected unavailable raw data.

## Prediction, AI, and omics

- Keep prediction distinct from causal explanation, biomarker association, diagnostic utility, and clinical benefit.
- Check participant-level separation across train/validation/test sets, preprocessing and feature selection within resampling, tuning, repeated measures, temporal or site leakage, and an untouched evaluation set.
- Consider discrimination, calibration, relevant operating thresholds, subgroup performance, transportability, and decision value. High internal accuracy or AUROC alone does not demonstrate clinical usefulness.
- For omics, inspect sample collection/handling, batch effects, normalization, quality control, high dimensionality, feature selection, multiple testing, effect sizes, and external replication. Flag reuse of discovery data as validation.
- For mechanistic claims, separate pathway enrichment or correlated markers from demonstrated biological flux or mechanism. Specify the experiments needed to distinguish competing explanations.
- For LLM studies, record actual model/version/date where known, prompts, settings, evaluation dataset, task definition, scoring, comparator, blinding where applicable, uncertainty, and contamination risks. Never invent hidden model versions or pretend full reproducibility when services change.

## Evidence synthesis and translation

- Check study eligibility, risk of bias, duplicated participants, heterogeneity, outcome/timepoint compatibility, reporting bias, and directness.
- Do not pool studies simply because pooling is possible. Explain whether estimates target a sufficiently compatible question; distinguish exploratory synthesis from a prespecified meta-analysis.
- Separate in vitro, animal, observational human, trial, and implementation evidence. Avoid implying clinical benefit from a surrogate association or preclinical mechanism alone.
- Describe applicability across populations, settings, prevalence, baseline risk, follow-up, and delivery conditions. Do not prescribe patient-specific treatment from a council output.

## Qualitative and other research

- Adapt the review to the epistemological approach and research aim. Assess sampling rationale, context, reflexivity, analytic transparency, grounding of interpretations, and discrepant cases where relevant.
- Do not impose statistical power, randomization, or universal numerical saturation thresholds on qualitative work.
- For theoretical or computational work, inspect definitions, assumptions, proof or algorithm validity, benchmarks, reproducibility, boundary conditions, and counterexamples; do not force clinical PICO framing.

## Research integrity and reporting

- Check protocol/registration timing, outcome switching, exploratory versus confirmatory labeling, ethics/consent reporting where applicable, funding/conflicts, and data/code availability.
- Do not infer misconduct from an inconsistency. State the discrepancy and request a check or clarification.
- Ensure the abstract, tables, figures, results, and conclusion agree. Preserve valid findings when narrowing overclaims.
- Prioritize remediable issues. Label a suggested new experiment as new work, not a revision the authors can claim to have completed.
