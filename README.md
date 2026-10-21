# Scientific Council

A Claude-compatible skill for critical appraisal of manuscripts, research questions, study protocols, statistical interpretations, and scientific claims, with particular attention to biomedical and healthcare research.

**Agreement between AI agents is not independent scientific evidence.** This skill asks reviewers to ground conclusions in inspected sources and appropriate methods, preserve uncertainty, and distinguish proposed work from completed analyses.

## What it does

A full council uses five complementary review roles:

1. Domain and mechanism
2. Study design and causal inference
3. Statistics and reproducibility
4. Evidence and citations
5. Scientific reporting and research integrity

Two fresh cross-review contexts examine the findings before the host synthesizes the assessment. When delegation is unavailable, the skill performs a clearly labeled single-agent appraisal. It does not pretend that simulated roles are independent reviewers.

Outputs include supported conclusions, prioritized concerns, concrete remedies, unresolved uncertainties, and revised scientific wording when requested.

## Install in Claude Code

Clone this repository into your personal skills directory:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/anthony-89/scientific-council.git ~/.claude/skills/scientific-council
```

If that destination already exists, inspect it first instead of overwriting it. Alternatively, copy `SKILL.md` and the complete `references/` directory into `~/.claude/skills/scientific-council/`.

For a project-specific installation, place those files in `.claude/skills/scientific-council/` within your project.

Invoke the skill with:

```text
/scientific-council Review this manuscript's methods and conclusions.
```

See the [official Claude Code skills documentation](https://code.claude.com/docs/en/skills) for environment-specific setup. For other Claude interfaces, ask Claude to install the complete skill folder using the mechanisms available in that interface; tool availability varies.

## Example requests

- “Stress-test this hypothesis and propose experiments that distinguish competing explanations.”
- “Review whether our observational results support the causal language in the discussion.”
- “Evaluate this AI literacy intervention, separating confidence, knowledge, competence, and behavior.”
- “Audit this prediction model for information leakage and unsupported clinical-utility claims.”
- “Check whether these references actually support our manuscript's central claims.”

## Files

| File | Purpose |
| --- | --- |
| [SKILL.md](SKILL.md) | Core workflow, reviewer roles, dispatch template, synthesis, and final audit |
| [references/evidence-protocol.md](references/evidence-protocol.md) | Evidence retrieval, claim–source ledger, citation verification, and reporting guidance |
| [references/methods-checklist.md](references/methods-checklist.md) | Conditional checks for design, statistics, AI, omics, qualitative research, and integrity |

## Validation and limitations

The skill passed structural validation and two illustrative single-agent research-case exercises: an uncontrolled education intervention and an observational biomarker/prediction study. These exercises were run outside Claude. They are not a benchmark, a test of the full multi-agent workflow, or evidence that this approach improves scientific accuracy.

No external packages, API keys, or custom scripts are required by the skill itself. Browsing, database access, and subagents depend on the host environment. Without retrieval, the skill limits its conclusions to provided material and reports that external literature was not verified.

## Acknowledgments

Independently written scientific adaptation of the workflow in [aiwithremy/claude-skills-llm-council](https://github.com/aiwithremy/claude-skills-llm-council). That repository credits Ole Lehmann and [Andrej Karpathy's LLM Council](https://github.com/karpathy/llm-council). Source provenance is recorded in `SKILL.md`.
