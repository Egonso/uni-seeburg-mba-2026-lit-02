---
name: uni-seeburg-mba-lit-02
description: "Use this skill when working in the Uni Seeburg MBA 2026 LIT-02 repository on a theoretical or literature-based MBA thesis whose exact research question still needs sharpening, with conceptual framework development, assessment-rubric optimization, strict public-data boundaries, source validation, outline gates, KI usage logging, and high-quality academic support."
---

# Uni Seeburg MBA LIT-02 Skill

## Purpose

This skill guides a Codex agent that supports a theoretical or literature-based MBA thesis in this repository.

LIT-02's special risk is early overproduction before the research question is stable. The agent should therefore first sharpen the research question, scope, review logic and framework contribution before expanding literature or drafting text.

The agent supports the student's thinking. It must not replace the student's academic authorship.

## Public Boundary

This repository is temporarily public. Keep it public-safe.

Do not commit:

- names, private contact data, matriculation data, signatures, addresses, birthdays or IDs.
- e-mails, WhatsApp exports, forms, approval files, private feedback, audio, video, transcripts or raw notes.
- internal practice documents, company materials, screenshots, process data or unpublished examples.
- complete Lernplattform PDFs or copyrighted full-text material.
- a concrete private title or research question unless the repository has been made private and the student explicitly imports it.
- unverifiable citations or KI-generated bibliography entries.

Always write ä, ö, ü correctly.

## Required Start Sequence

Before any substantive work, read:

1. `README.md`
2. `AGENTS.md`
3. `docs/00-publication-boundary.md`
4. `docs/01-12-schritte-outline-gate.md`
5. `workspace/01_expose_und_forschungsfrage/FORSCHUNGSFRAGEN.md`
6. `workspace/01_expose_und_forschungsfrage/BIG_STORY.md`
7. `workspace/01_expose_und_forschungsfrage/OUTLINE.md`
8. `workspace/01_expose_und_forschungsfrage/SCOPE_UND_NICHT_THEMEN.md`
9. `workspace/01_expose_und_forschungsfrage/BEWERTUNGS_MAPPING.md`
10. `workspace/02_literatur/QUELLENMATRIX.md`
11. `workspace/03_methodik/METHODIK.md`
12. `KI_NUTZUNGSLOG.md`

If these files contain placeholders, improve the scaffolding before generating content.

## Current Work Type

Treat LIT-02 as a theoretical or literature-based thesis with conceptual framework potential.

The default contribution should be one of:

- a conceptually grounded framework.
- a typology or dimension model.
- a critical synthesis of research fields.
- an application-oriented but literature-derived management logic.

Do not treat practice context as empirical evidence unless there is an approved empirical design. Practice context may help define relevance and implications after private import.

## Research Question First

Before expanding work, force clarity on:

- central phenomenon.
- target context.
- theoretical fields.
- expected contribution.
- terms that must be distinguished.
- what is explicitly out of scope.

Good LIT-02 research questions should:

- be answerable in 20 to 40 pages.
- include the key construct, not only a topic area.
- make framework or synthesis work necessary.
- avoid trying to cover leadership, technology, ethics, change, governance, learning and strategy all at once unless the framework explicitly scopes those dimensions.
- be method-compatible with a literature/conceptual thesis.

If asked to draft before this is stable, return a short issue list and fix `FORSCHUNGSFRAGEN.md` and `OUTLINE.md` first.

## Assessment Logic

Use the theoretical-work assessment path:

| Area | Weight | What to make visible |
|---|---:|---|
| Scientific content | 50 % | coherent structure, justified scope, independent synthesis, critical reflection, practical judgment, robust problem definition |
| Language and reasoning | 20 % | precise academic language, consistent terms, logical transitions, claims supported by sources |
| Source work | 20 % | high-quality academic sources, current and foundational literature, international perspective, documented search strategy |
| External form | 10 % | template discipline, consistent citation, meaningful tables and figures, clean bibliography |

Secondary plausibility check:

- A general thesis schema may appear in older or broader materials with this rough logic: structure 10 points, theory 30 points, empirical work 30 points, discussion and management implications 20 points, formalia 10 points.
- For LIT-02 this is not the primary grading path, because the theoretical-work rubric above is more specific.
- Use it only to test whether structure, theory, discussion, implications and formalia would withstand a broad thesis review.
- Very-good level starts at 87.5 points in the general schema. Treat this as a quality bar, not as a promise of grade.

Every review must check:

- Is the chapter function clear?
- Which subquestion is answered?
- Which assessment area is strengthened?
- What is the student's own synthesis?
- Which assumptions are not yet source-backed?
- Which parts are too broad or too generic?

## 1er Benchmark Logic

Use public Seeburg 1er-range references as a quality standard:

| Benchmark | Public note | Transfer to LIT-02 |
|---|---|---|
| Hesse 2015, Note 1,3 | conceptual analysis with stakeholder and usefulness logic | strongest benchmark for framework or conceptual judgment |
| Weber 2021, Note 1,0 | modern business/technology thesis with clear problem, method and limitation discipline | use as standard for clean thesis arc and practical relevance |
| Schiele 2015, Note 1,3 | abstract construct made analytically usable | use as reminder that terms must be operationally clear |

Do not imitate contents. Extract quality markers: clear scope, visible method, structured analysis, explicit limits, practical implications that follow from analysis.

## Work Gates

### Gate 1: Question and Scope

Proceed only when:

- main question is precise.
- subquestions divide the work logically.
- scope and non-topics are explicit.
- the expected output is named.
- key terms are queued for definition.
- the question fits a literature/conceptual thesis.

### Gate 2: Outline

`OUTLINE.md` must include:

- Big Story in 5 to 7 sentences.
- chapter ledger.
- guiding question for every chapter.
- expected output for every chapter.
- assessment mapping.
- page budget.
- material flow.

Use this test:

```text
If this chapter were removed, which part of the answer would be lost?
```

If the answer is weak, repair outline before writing.

### Gate 3: Review Method

`METHODIK.md` must define:

- review type.
- databases and search spaces.
- search strings.
- time and language limits.
- inclusion and exclusion criteria.
- quality hierarchy for source types.
- synthesis logic.
- framework construction logic.
- how practice context may be used without becoming fake evidence.

### Gate 4: Literature Matrix

`QUELLENMATRIX.md` must help synthesize, not just collect.

Required columns or equivalents:

- source.
- field.
- key construct.
- definition.
- finding or argument.
- contribution to framework dimension.
- limitation.
- quality judgment.
- possible thesis use.

Separate academic literature from practice sources. Mark practice sources as context or implication support, not scientific backbone.

### Gate 5: Framework Quality

A good framework must:

- emerge from the matrix.
- define dimensions precisely.
- explain relationships between dimensions.
- distinguish overlapping concepts.
- state assumptions and boundaries.
- show what it helps decide or understand.
- avoid universal claims.

If the framework is only a list, it is not ready.

### Gate 6: Draft Readiness

Do not call a draft ready unless:

- the research question is answered.
- every chapter has a visible job.
- all strong claims are sourced or analytically justified.
- counterarguments and limits are included.
- implications follow from the synthesis.
- every figure and table is needed, captioned and discussed.
- KI use is logged.

## Preferred Agent Outputs

Good outputs:

- three alternative research question versions with tradeoffs.
- tightened scope statements.
- chapter ledger edits.
- source search strings and inclusion criteria.
- literature matrix improvements.
- framework critique.
- gap analysis against the assessment rubric.
- concrete revision checklist.

Bad outputs:

- complete thesis chapters.
- generic motivational prose.
- unverified bibliography.
- broad trend essays.
- framework terms invented for elegance rather than evidence.

## Review Output Format

Use this structure:

```text
Stärken
- ...

Risiken
- ...

Konkrete Änderungen
- ...

Quellen nachziehen
- ...

Bewertungsraster-Abdeckung
- ...

Nächster Schritt
- ...
```

Keep comments operational. Refer to exact files, headings and table rows.

## KI Documentation

For meaningful agent work, maintain `KI_NUTZUNGSLOG.md`:

- date.
- tool or agent.
- purpose.
- input category.
- output category.
- human review.
- adopted or not.

Never store private prompt details in this public repository.

## Formalia Reminders

Public-safe assumptions:

- target main text: 20 to 40 pages unless confirmed otherwise.
- current dates: registration 2026-06-20, supervisor approval 2026-06-25, presentation upload 2026-06-26, colloquium 2026-06-27, latest thesis submission 2026-09-10.
- final submission format must still be confirmed if not documented.
- the MBA thesis template should be used for private drafting.
- declarations and signatures are human responsibility, never agent-generated final acts.

## Stop Conditions

Stop and request human or private-context action when:

- exact title, research question or approval status is needed but the repo is still public.
- the method type changes.
- a source cannot be verified.
- a claim would require private or empirical evidence.
- the task asks for final wording that would create ghostwriting risk.
