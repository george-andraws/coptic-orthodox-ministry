# Historical Precedent Use Policy

Bible-study projects may contain dated reference files from earlier work. They are valuable, but they are not all current standards.

Use this policy whenever a task loads an older book/session precedent, audit pattern, rewrite pattern, or publication-refresh pattern.

## Rule

Historical precedent files answer: what worked or failed in a prior project?

Shared standards answer: what should be done now?

When they conflict, current shared standards win unless the project owner explicitly asks to preserve the older structure for that book.

## Current shared standards to prefer

Consult these shared references as needed:

- `bible-study-quality-contract.md`
- `bible-study-guide-structure-standard.md`
- `bible-study-source-pack-template.md`
- `orthodox-depth-bar.md`
- `patristic-sourcing-policy.md`
- `patristic-quote-gems-and-direct-footnotes.md`
- `orthodox-visual-assets.md`

## How to use a historical precedent

Extract only the durable pattern:

- book-specific source pitfalls;
- known lectionary findings;
- known patristic anchors and their source-status limits;
- verified grouping/split rationale;
- hard-text guardrails;
- visual/source/license lessons;
- verifier or bookkeeping pitfalls;
- user corrections.

Do not inherit stale forms such as:

- `## Navigation` in guide bodies;
- duplicate body H1s;
- front-loaded full Scripture sections without interleaved explanation;
- `## Teaching guide` for newly migrated Bible-study guides;
- `Teaching Notes / Discussion Questions` as a section title;
- nested `### Teaching Notes` under `## Spiritual Fruit 🍇` when the adopted structure standard expects `## Teaching Notes` as H2;
- grouped end-of-guide language-note appendices when the note belongs under a passage;
- reader-facing local/tooling/source-process wording.

## Banner for old references

When editing an old reference because it is still useful but structurally stale, add this near the top:

```markdown
> Historical precedent. Current Bible-study structure and quality rules are governed by `bible-study-quality-contract.md` and `bible-study-guide-structure-standard.md`. Preserve this file's durable source/workflow lessons, but do not copy older headings or structure when they conflict with the current standard.
```

Do not mass-edit every old reference only to add the banner. Add it opportunistically when a file is already touched or when the stale pattern caused a real mistake.

## Selective book knowledge for existing-guide revision

Resolve the exact book/aliases, passage, edition/frame and task mode first. Consult an existing project reference index as a locator, then read only the matching subsections and relevant genre questions below, applying edition/source-frame checks additionally whenever material. An adjacent book's precedent supplies a method, not evidence for this book. If no relevant verified knowledge exists, do targeted research rather than loading near-matches.

Use existing reference owners rather than creating a separate system for each book:

- Shared references own reusable methods and source/edition safeguards.
- Substantive book knowledge belongs in the existing book overview, source list or research note. Extend a small `Revision knowledge` section or an existing topic before creating another note. Writing that knowledge still needs task authority; this policy does not authorize unrelated document maintenance.
- Existing project precedents retain checked source anchors, edition crosswalks and recovery lessons in their owning references. A registry points to the owner rather than copying the claim into a second authority.
- Transient execution state and incident chronology remain project records, not standing book knowledge.

A compact registry entry needs **book/aliases | passage/scope | topic | owning note/reference | applicability**. Search first; do not create a second index if the current registry already covers the book.

Within the owning book note, a reusable knowledge item records **claim or editorial caution; precise applicability; relevant edition/source/version; evidence locator; verified, thematic/inferred, disputed or historical status; the mistake it prevents or insight it enables; primary guide location and cross-reference policy**. Reverify on meaningful evidence change, not an arbitrary expiry that forces repeated research. Preserve uncertain claims as uncertain; a registry entry does not certify them.

Examples of selective ownership, not newly verified theological findings:

- John 6 eating vocabulary stays in the lexical standard's John 6 subsection and relevant John resources; it cannot alone prove Eucharistic doctrine or become a mandatory note elsewhere.
- Job speaker/argument cautions stay with Job's existing book resources; an interlocutor's speech is not automatically the narrator's or the Church's conclusion.
- Greek Daniel, Esdras and Nehemiah crosswalks load only for affected edition/frame questions; compare contents and source labels, not guessed offsets.
- Philippians argument and hymn observations stay with its book resources and matching precedents, not a universal epistle formula.
- Worship findings carry the actual day/service/edition and evidence tier; thematic resonance does not create an appointment.

## Optional genre and frame lenses

These are internal editorial questions, not mandatory reader headings or new mini-standards. Use only what matches the passage.

| Lens | What to inspect |
|---|---|
| Narrative / Gospel | Recorded action, sequence, speaker and meaningful gaps; distinguish text from historical reconstruction, later remembrance and pastoral meditation. Do not invent scene detail or motives. |
| Epistle / argument | Connectors, objections, paragraph logic and the book's actual burden. An argument-led opening can engage without a scene or typology table. |
| Wisdom / lament / poetry | Speaker changes, parallelism, provisional claims, unresolved complaint and prayer. Do not make every proverb exceptionless or rush lament into a generic solution. |
| Prophecy / apocalypse | Literary unit, biblical intertexts, audience, doctrinal certainty versus disputed detail, and hope without speculative certainty. Use `orthodox-apocalyptic-exegesis` only when the passage calls for it. |
| Edition / source frame | Adopted text, exact content boundaries, printed labels, reordering, omissions and verified crosswalks. Same verse numbers do not prove the same text or appointment. |

Truth and pastoral safety are checked independently of a reader's stylistic preference. Preserve the strongest existing explanation when a proposed lens adds no useful insight.
