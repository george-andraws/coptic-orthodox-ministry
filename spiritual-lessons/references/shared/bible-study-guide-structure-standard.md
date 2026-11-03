# Bible-study guide structure standard

Canonical standard for exact section syntax in Orthodox Bible-study guide files. Use it for new guides and authorized structural migrations. During bounded revision, preserve the existing approved form unless structure is a named defect within scope; a readiness finding can propose migration without authorizing it. [`bible-study-quality-contract.md`](bible-study-quality-contract.md) owns substantive acceptance, comparative gain and release blockers. Optional apparatus is not a section quota.

## Exact section-title contract

When organizing or updating Bible-study content into these sections, use these exact titles word-for-word, including the emoji at the end of the line:

- `Geographical Significance ⛰️`
- `The Characters 👥`
- `Light from the Word 🕯️` for Old Testament or general scriptural insights
- `Light from the Gospel 🕯️` for New Testament / Gospel-specific insights
- `Iconography Connection 🖼️` or `Iconography and Visual Teaching 🖼️`
- `The Church's Voice in Worship ⛪`
- `Spiritual Fruit 🍇`
- `Gems from the Fathers 💎` for a single Gems subsection, or `Gems from the Fathers 💎: <specific subtitle>` for each of multiple Gems subsections

During an authorized structural migration, convert old or variant headings to this contract. An inspect-only audit reports deviations, and a bounded correction preserves the approved form unless migration is in scope. Convert `In the Fathers`, `Patristic Depth`, and un-emojied `Gems from the Fathers` to `Gems from the Fathers 💎` when migrating. Convert `The Text Broken Open` to `Light from the Word 🕯️` for Old Testament or general Scripture work, and to `Light from the Gospel 🕯️` for Gospel-specific New Testament work.

### NT session-guide note

Most New Testament **session guides** do **not** wrap the whole body under one `## Light from the Gospel 🕯️` heading. The controlling form is interleaved H2 passage sections with the Scripture reference in each H2. Use the emoji-named sections above when they truly help as orientation or support sections, or when an older project form already depends on them. Do not force OT publication-batch sections such as separate “Orthodox Theological Reading,” “Christological Types and Prophecies,” or “Closing Meditation” onto NT session guides unless that shape is explicitly requested. Christology, worship, and spiritual application normally live inside the passage explanations and `## Spiritual Fruit 🍇`.

For Gospel narrative and other typological NT studies:

- Give a real context paragraph before commentary: setting, people, place in the book, and Evangelist order when it matters.
- A compact Promise in Israel / the sign or event here / fulfillment in Christ table may appear after the explanation when verified connections become clearer in that form. Omit it if prose already does the work or if the passage does not support it; do not manufacture typology.
- Let Spiritual Fruit end as the passage warrants: prayer, consolation, a concrete response, praise or a text-rooted meditation. A scene is optional, never invented and never a fixed sentence quota. Do not add a compulsory `## Closing Meditation` heading.
- When another published study is mentioned, make the reference text itself a site-absolute link. Do not print the path as visible prose.

## Reader-facing guide body

Guide/article files themselves should not contain `## Navigation` sections or internal knowledge-base navigation links. Keep navigation links in indexes, status notes, resources notes, and audit notes.

The body is for clean reader-facing study prose:
- begin after frontmatter with a lead/opening paragraph, not a duplicate H1 or navigation block;
- orient the reader briefly;
- move passage by passage through natural sense-units;
- for session guides, make each natural Scripture unit an H2 passage heading that includes the reference and contains the blockquoted Scripture; do not put all passage units as H3s under a wrapper H2 such as `## Light from the Gospel 🕯️`;
- interleave quoted Scripture with explanation and application;
- include relevant Greek, Hebrew, Aramaic, Septuagint, or translation-shape insights inside the specific passage section they illuminate, immediately under that Scripture unit's explanation; do not collect them into a standalone end-of-guide language-notes section;
- keep teaching directives out of the exposition;
- keep `## Sources and Further Reading` as the final H2 section at the very bottom of the guide when present;
- do not mention internal project resources, local tooling, private files, query helpers, audit roadmaps, or process notes in reader-facing source sections. If a cited source has a public URL, include the direct URL; if it has no public URL, cite it plainly without inventing one;
- when a guide has a distinct patristic subsection, title a single one `### Gems from the Fathers 💎` or `## Gems from the Fathers 💎` depending on the existing heading level. When more than one appears, use `### Gems from the Fathers 💎: <specific subtitle>` or the matching H2 form and give every subtitle a unique, reader-meaningful description. Do not let the section become a passing reference list. Preserve or add an explanatory summary/paraphrase of what the Father is teaching about the passage, then add verified direct quotations when the wording is eloquent, significant, or spiritually useful.
- when a substantive verified Coptic or Orthodox worship connection is present, place `### The Church's Voice in Worship ⛪` under the passage it illuminates. Put it after the lead only when the worship connection governs the whole guide; do not bury a full lectionary rationale in an unheaded introduction paragraph.
- when direct patristic quotations appear, attach a portable Markdown footnote to each quote. The footnote itself should contain the short citation and direct/deep URL. Do not make the footnote link to a separate source-list item as an intermediate hop. `## Sources and Further Reading` may still use numbered lists for readability, but quote footnotes should cite directly.

## Spiritual Fruit and Teaching Notes

Each new or substantially revised Bible-study guide should contain exactly one `## Spiritual Fruit 🍇` section followed by one `## Teaching Notes` section near the bottom, with `## Sources and Further Reading` remaining the final section when present.

`## Spiritual Fruit 🍇` is reader-facing spiritual application. It must grow from the verses already explained and give concrete benefit for prayer, repentance, worship, mercy, watchfulness, family life, service, lament, praise or endurance in Christ. Generic uplift such as “be more faithful” fails unless sharpened by the passage's actual claim. Choose length and form by interpretive value, not fruit counts or a uniform ending. Use the quality contract for acceptance and the NT/voice references for targeted craft coaching; a scene-placed meditation is optional.

Use this shape:

```markdown
## Spiritual Fruit 🍇

<Reader-facing spiritual fruit and practical application.>

## Teaching Notes

### <Plain passage label with its Scripture reference>
- Ask: <discussion question>
- Watch for: <common misunderstanding or pastoral caution>
```

Teaching-note passage labels must be plain text. Do not use knowledge-base backlinks or same-page heading links such as `[[#...]]` in guide-body teaching headings. Ask, Emphasize, Watch for, Connect and Show are available categories, not a mandatory five-bullet grid. Default to one Ask and one Watch for per passage. Add Emphasize or Connect only when they serve a distinct teaching need rather than repeat the commentary. Add Show only when the named visual is actually present on the same page; pointing to an illustration on another study is not enough. Preserve explicitly approved fuller teaching formats and the passage-local lesson-guide format below.

## Term, concept, language, and translation insights

Technical terms are part of teaching, not decoration. Define Greek, Hebrew, Aramaic, Syriac, Coptic, patristic, liturgical, iconographic, historical, and doctrinal terms when a faithful parish reader or servant may not know them. Define the term briefly, then explain why it matters for this passage or practice.

Language insights belong to passage exegesis, not an appendix. Investigate a Greek, Hebrew, Aramaic, Septuagint or translation-shape issue when it materially affects this passage. Record the observed textual fact, supported interpretive consequence and gain to this reader under [`lexical-and-translation-depth-standard.md`](lexical-and-translation-depth-standard.md). Checked with no useful addition is a valid result, not a missing section.

When discussing *words or phrases as words*, enclose each mentioned term in quotation marks in reader-facing headings and prose, including language-insight subtitles and lists. Write `Language insight: “witness”, “right”, and “children of God”`, not `Language insight: witness, right, and children of God`. Distinguish a word being named from an ordinary use of that word in a sentence; do not quote every occurrence. Preserve approved Scripture quotations exactly rather than changing their punctuation for this style rule.

A good language note should reveal something the English reader would likely miss: movement or escalation in the passage, distinct original words hidden behind one English word, source-shape or numbering differences that affect interpretation, wording that supports patristic or liturgical reading, or a guardrail against a shallow or false reading. For New Testament guides, actively look for meaningful Greek or Aramaic depth when the text warrants it: Logos behind “Word,” Paraklētos behind “Helper” or “Comforter,” distinct Greek love words hidden behind English “love,” or other repeated/theological terms that shape interpretation. The John 6 eating-verbs discussion is a passage-specific precedent, not an obligatory lexical model for other texts. Consult that passage-specific discussion only for John 6 or a directly relevant comparison; a contextual verb contrast alone cannot establish doctrine.

When a language note meets that bar, add it directly under the passage section it explains, usually as a short paragraph or a `### Language insight` subsection. The note must define the term plainly and then explain why the wording matters for meaning, worship, patristic use, doctrine, or spiritual application. Do not use `### Language insight` for generic English-phrase explanation. For example, “He who sent me places John's ministry under divine command” may be a valid exegetical sentence, but it is not a linguistic insight unless the original wording, term choice, or translation shape itself deepens the reading. Omit the subsection when there is no meaningful insight; do not pad with lexicon trivia or isolated word definitions.

Do not create a late language-note catch-all in new guides or authorized structural migrations. Migrate an older appendix into its relevant passage sections only when structural migration is in scope; preserve its useful content and exact source claims. An audit reports the deviation, and a bounded factual correction leaves the approved form intact.

## Consolidation rule

When passage-local lesson-guide boxes are explicitly approved, retain that form instead of applying the legacy consolidation rule below. Verify that the publication format preserves these boxes in the intended reading and print views. Let each local box supply Key phrases/Emphasize/Avoid. Default bottom Teaching Notes to Ask/Watch for that adds distinct questions and pastoral cautions, and compare their sentences with the local boxes to remove exact or near duplication. Do not duplicate a local Emphasize sentence at the bottom merely to fill the general template.

Otherwise, during an authorized structural migration of legacy `Lesson guide`, `Teacher's Notes` or `## Teaching guide` fragments, do not merely move them unchanged. An inspect-only audit reports consolidation needs; a bounded revision preserves the approved form.

When consolidation is authorized, rework them into a coherent teaching guide for the whole study:
- name the study's main teaching burden when helpful;
- organize helps passage by passage with plain labels;
- combine duplicate or overlapping prompts;
- keep teacher actions practical and specific;
- make the teaching notes serve the whole guide rather than preserve the old fragment layout.

## Legacy structures

Legacy `## Teaching guide` sections and Obadiah-style linked teaching headings are historical patterns only. They solved local transition problems but are too noisy and fragile for future audits.

During an authorized structural migration, use the canonical `## Spiritual Fruit 🍇` followed by `## Teaching Notes` structure. An audit can report migration needs without changing files; a bounded revision preserves approved form unless migration is in scope.

## Structural verification

After creating or substantially revising a session guide, check the saved Markdown for legacy `## Teaching guide` structure, same-page teaching links, navigation sections, duplicate-title starts, and the required bottom `## Spiritual Fruit 🍇` followed by `## Teaching Notes` structure. Use automated checks when available, but do not treat mechanical success as proof of substantive quality.
