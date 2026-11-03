# Bible Study Source Pack Template

Use this template before drafting or substantially revising an Orthodox Bible-study guide. The source pack is a compact bridge between research and guide prose. It keeps source work explicit without leaking tool/process language into the reader-facing guide.

## When required

Create or update a source pack when:

- drafting a new session guide;
- revising a weak or no-Fathers guide;
- continuing a book project after a gap;
- handling hard texts, deuterocanonical material, divergent LXX/NKJV numbering, or complex lectionary claims;
- using delegates or external reviewers;
- publication-ready or final-quality work is requested.

For a tiny passage explanation that will not be saved as a guide, a mental/brief source pack is enough. For existing-guide revision, reuse the accepted pack and update only unresolved, changed or newly introduced evidence; no-Fathers status alone is not a defect when omission is appropriate. Do not reopen every source to demonstrate effort.

## Editorial record

Keep the source pack separate from the reader-facing guide, using the project's agreed editorial-record convention. It may record searches and evidence limitations; the final guide should not expose research machinery.

## Compact source pack schema

```yaml
session:
book:
passage:
guide_reference:
revision_delta: # existing-guide revision only; omit for new work
  baseline_identity:
  approved_form_and_allowed_writes:
  actual_defects_and_expected_gains:
  protected_strengths_and_book_insights:
  evidence_reused_and_unresolved:
  candidate_identity:
  comparative_gains_losses_and_length:
  acceptance_and_remaining_gaps:
source_text:
  translation: NKJV | Brenton LXX | other
  source_method: verified edition | supplied text | other
  rights_or_distribution_note:
  verse_coverage:
  numbering_notes:
  reader_facing_psalm_citations:
    - mt_form:
      lxx_form:
      verified_source:
      use_in_guide:
movement_divisions:
  - heading:
    reference:
    reason_for_boundary:
scriptural_cross_references:
  - reference:
    reason:
patristic:
  direct:
    - father:
      work:
      passage_or_section:
      quote_status: quote_eligible | paraphrase_only | needs_verification
      citation_url:
      guide_use:
  thematic:
    - father:
      work:
      theme:
      honesty_label:
      guide_use:
  absence_wording:
lectionary:
  source_title:
  edition_or_version:
  provenance:
  reference_frames_checked:
  exact_hits:
    - service_or_day:
      passage:
      confidence: confirmed | likely | uncertain
      reader_facing_body_claim:
      source_note_limits:
      guide_section: The Church's Voice in Worship ⛪ | inline only
      spiritual_logic:
  no_exact_hit_wording:
language_or_lxx_notes:
  - term_or_phrase:
    original_term:
    lexical_or_translation_observation:
    why_it_matters_for_this_passage:
    overclaim_guardrail:
    source_urls:
visuals:
  - type: icon | map | manuscript | museum object | Western art | generated schematic
    source_reference_or_url:
    teaching_purpose:
    rights_or_caution:
hard_text_guardrails:
  - verse_or_line:
    risk:
    body_guardrail:
teaching_burden:
spiritual_fruit:
open_questions:
derivative_artifact_status:
```

## Minimum viable source pack

When context is tight, capture only:

1. target guide and passage;
2. verified Scripture source and verse coverage;
3. passage divisions with reasons;
4. strongest patristic direct/thematic anchors or honest absence;
5. verified lectionary hits or honest absence;
6. hard-text guardrails;
7. visual/source notes if relevant;
8. derivative artifact status, when relevant.

## Quality rules

- The source pack should be terse and evidence-rich.
- Do not paste massive raw source output. Summarize, then fetch exact selected source text only when needed.
- Treat language or translation-shape observations under `language_or_lxx_notes` as weight-bearing evidence, not filler. Apply [`lexical-and-translation-depth-standard.md`](lexical-and-translation-depth-standard.md): record the original term or source-shape issue, why it matters for this exact passage, the overclaim guardrail, and source URLs when online lexical/interlinear sources are used. For NT source packs, actively check for meaningful Greek or Aramaic terms when the text warrants it, such as Logos / “Word,” Paraklētos / “Helper” or “Comforter,” Greek love-word distinctions, repeated roots, or theological terms hidden by a flat English rendering. Do not record generic English-phrase explanations as language notes; put those in normal exegesis only if they are useful.
- If a source was searched and found nothing useful, record the scoped absence once.
- Treat Coptic Treasures and index tools as leads unless the direct source has been verified.
- If a research assistant produces the source pack, the responsible author must verify the selected facts before guide prose is written.

## Compact role briefs: creation, review and revision

Use these briefs within the agreed editorial review format, not as a new mandatory schema. Supply the full baseline/candidate and relevant source evidence; a reviewer cannot establish whole-guide quality from selected highlights. Specify the exact scope, protected Scripture/metadata, source rights, checked lectionary source edition and permitted changes. Feedback is evidence to adjudicate, not new authority.

**Creation / substantive revision brief:**

> Read the complete passage and, for revision, the complete baseline. Name the actual tension or promise and the decisive textual details; explain them in context before selecting apparatus. Develop warranted meaning in Christ and a credible response of grace, without forcing the same devotional sequence on every unit. Protect the supplied strong lines/insights unless correction requires a loss. Use only sources that illuminate this passage, honor quote/paraphrase limits, and keep necessary safeguards beside risky claims. After the meaning is sound, improve cadence and remove repetition. Return the guide plus a concise account of concrete gains, material losses and unresolved limits in the assigned artifact. No change is valid for already sound prose.

**Independent review brief:**

> Read the complete candidate, baseline/diff and supplied evidence. Apply the one shared quality rubric. Check Scripture and difficult clauses, exact attribution and source qualifications, warranted spiritual benefit and whole-guide flow. Locate a material gained or lost strength rather than making a generic preservation claim. For every required issue, citation or worship claim, give a specific claim/location and source/context basis; preserve unresolved source status even when prose is safely qualified. Distinguish required repairs, unresolved evidence and optional craft suggestions. Do not assume unseen checker logs passed or belong only to an allowed exception. Bind the verdict to exact candidate bytes; acceptance does not install or publish them.

**Targeted correction brief:**

> Preserve the reviewed candidate and receipts before editing. For each finding choose accept, adapt, reject with evidence, or unresolved; give a brief reason and the smallest useful repair. Correct meaning/source/safety first, recover useful lost strengths when sound, then improve proportion and rhythm. Reconcile the changed claim wherever it recurs in this guide, preserving unrelated strong prose and protected bytes. Record superseded evidence separately; freeze changed bytes for affected independent acceptance. Do not restart the guide or add apparatus merely because a reviewer preferred a longer version. Hold unresolved blockers without repeated rerolls.

For worked prose and evidence examples, consult [`spiritually-edifying-exegesis-voice-standard.md`](spiritually-edifying-exegesis-voice-standard.md). Do not paste its examples as stock paragraphs.

## Handoff to drafting

Before drafting, convert the source pack into a short guide plan:

- H2 passage headings;
- one burden sentence per passage;
- exact patristic placement decisions;
- exact lectionary/source wording;
- hard-text guardrail locations;
- Teaching Notes labels matching body passage sections.

After drafting, verify that every planned anchor actually landed in the saved guide. Do not report intended anchors as if they were written.
