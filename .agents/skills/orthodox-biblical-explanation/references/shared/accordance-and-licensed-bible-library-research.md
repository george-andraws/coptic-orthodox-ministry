# Accordance and Licensed Bible-Library Research

Use this reference when an Orthodox lesson or Scripture explanation could benefit from a lawfully licensed Bible-study library such as Accordance.

## Access and activation boundary

Use only resources the user lawfully owns or may access. An account license does not prove that every named module is owned, installed, searchable, exportable, or reusable in a public artifact.

For Accordance Desktop:

1. Obtain the desktop installer from the [official Accordance downloads page](https://www.accordancebible.com/download-accordance/).
2. On macOS, verify the OakTree Software code signature and Gatekeeper/notarization assessment. On Windows, verify the Authenticode publisher before installation.
3. The account holder signs in within Accordance. Never ask an agent to store, print, or publish the password.
4. Use **Accordance > Easy Install** on macOS, or **Utilities > Easy Install** on Windows, to download purchased modules.
5. Inventory the modules actually shown in the user's library before promising any source coverage.
6. Record only module titles and research capabilities in durable workflow notes. Do not publish credentials, account identifiers, proprietary module files, internal databases, private paths, or transformed corpora.

Official help: [Install Accordance Desktop and purchased modules](https://support.accordancebible.com/hc/en-us/articles/35803862742427-Install-Accordance-Desktop-and-Install-Purchased-Books-Modules).

If Accordance or the required module is unavailable, record a scoped coverage gap and continue with approved Scripture, patristic, Coptic, liturgical, academic, library, museum, and web sources. Never imply that Accordance was searched when it was not.

## Choose sources by evidence role

Treat installed modules as research candidates, not authorities merely because they are present.

### Orthodox and patristic orientation

| Resource type | Best role | Guardrail |
|---|---|---|
| Orthodox study Bible | Orthodox bridge notes, typology, sacramental and spiritual orientation | Verify specifically Coptic claims through Coptic sources. |
| Patristic anthology | Discover passage-linked Fathers, works, and primary-source leads | Verify decisive quotations in the underlying work when possible. |
| Early-Christian biography/reference | Chronology, councils, controversies, writings, and relationships | Historical orientation is not itself Orthodox doctrinal authority. |

### Scripture and translation comparison

| Resource type | Best role | Guardrail |
|---|---|---|
| Septuagint-based English Old Testament | Orthodox-canonical and translation comparison | An English translation is not the Greek Septuagint. |
| Tagged English Bible | Wording comparison and initial lexical identifiers | Tags and glosses do not replace syntax, context, and stronger lexica. |
| Greek or Hebrew text | Original-language wording and linked research | Identify the edition and textual base; do not flatten textual differences. |
| Deuterocanonical text | Locate and compare material across canons and versification | State naming and numbering differences clearly. |

### Lexical orientation

| Resource type | Best role | Guardrail |
|---|---|---|
| Concise lexicon | Lemma, frequency, sense range, and representative references | Determine the passage's sense from syntax, argument, and wider usage. |
| Strong's-style dictionary | Quick identifier and traditional gloss orientation | Insufficient for nuanced semantic or theological claims by itself. |

### Geography, history, and visual teaching

| Resource type | Best role | Guardrail |
|---|---|---|
| Bible atlas | Routes, terrain, borders, kingdoms, exile, and why places matter | Label disputed dates, borders, and site identifications. |
| Charts, maps, and reconstructions | Architecture, cities, sequences, comparisons, and material culture | A reconstructed scene is a reasoned proposal; it is neither a camera record nor proof that every detail is settled. |
| Bible dictionary | People, places, institutions, archaeology, and cultural background | Academic/ecumenical background is not Orthodox doctrinal authority. |
| Site photographs and historical views | Landscape, archaeology, and traditional identifications | Distinguish archaeological evidence from later tradition and check image rights. |
| Bible-art index | Discover creators, dates, and passage-linked works | Western religious art is not Orthodox iconography or historical proof. |

### Passage discovery and comparison

| Resource type | Best role | Guardrail |
|---|---|---|
| Gospel or Synoptic parallels | Compare corresponding episodes and canonical emphases | Preserve each Gospel's final canonical form. |
| Epistle parallels | Find recurring language and related themes | Similar wording does not prove identical context or purpose. |
| Parables or miracles index | Locate occurrences quickly | An index is not commentary. |
| Translation notes | Identify textual or translation decisions | Translation apparatus is not Orthodox interpretation. |

## Retrieval workflow

1. Define the research question: interpretation, Father, wording, lexicon, geography, architecture, chronology, parallel, chart, or visual.
2. Select one to three resources that fit the evidence role. Do not search every installed module merely to claim coverage.
3. Use a narrow source-scoped query first. Broaden only after the focused search fails.
4. Open the complete entry or page and adjacent context before quoting, paraphrasing, or drawing a conclusion. Search snippets are leads only.
5. Record enough provenance to relocate the evidence: resource title, author/editor, module name when useful, entry/page/section, printed-page alias when reliable, and access date.
6. Label the evidence role: Scripture text, Orthodox bridge, direct patristic witness, anthology excerpt, lexical orientation, modern scholarship, historical reconstruction, or visual lead.
7. Verify exact quotations, sensitive theology, disputed history, and load-bearing claims against fuller primary or authoritative sources when possible.
8. Use a licensed library alongside, not instead of, Coptic sources, direct patristic works, liturgical sources, and current scholarship.

A failed search proves only that the material did not surface in the modules and search scope checked. It does not prove that a work, interpretation, or tradition does not exist.

## Application access

Use the desktop application when the task needs application-specific functions such as indexed Scripture searches, original-language tagging, linked lookup, aligned parallels, interactive atlas/timeline tools, or exact application rendering.

Do not scrape or reverse-engineer proprietary module files. If the software exposes a lawful user export, preserve the citation and license restrictions. Prefer deterministic, documented exports for repeated research, but never redistribute protected text or images merely because they are stored locally.

### Accordance automation on macOS

Accordance 14 ships OakTree-signed Automator actions for retrieving Scripture text and opening a reference or search in Accordance. Prefer those application-level interfaces to direct access of proprietary module databases.

After the account holder has signed in and completed Easy Install, the application can return its installed text-module names through its documented AppleEvent:

```bash
osascript -e 'tell application "Accordance" to return «event AccdVerL»'
```

To retrieve a valid verse reference from an exact text-module name, pass values as arguments rather than embedding untrusted strings in AppleScript source:

```bash
osascript \
  -e 'on run argv' \
  -e 'tell application "Accordance" to return «event AccdTxRf» {(item 1 of argv), (item 2 of argv), false}' \
  -e 'end run' \
  -- "$MODULE_NAME" "$SCRIPTURE_REFERENCE"
```

These boundaries matter:

- The module-list event covers Bible text modules, not every commentary, atlas, chart, or research tool.
- The text-reference event accepts Scripture references in text modules; it is not a bulk commentary exporter.
- Use the application interface for tool searches and record the exact resource and locator manually.
- Never put an Accordance username or password in AppleScript, a shell command, or a durable note.
- An empty text-module response before sign-in or Easy Install means the setup is incomplete, not that the account owns no resources.
- Licensed output keeps the same quotation, citation, and redistribution limits whether it is copied manually or returned through automation.

## Visual and rights discipline

For atlas, chart, photograph, artwork, or reconstruction material:

- inspect the actual visual before saying it illustrates the passage;
- record creator/publisher, caption, date, identification, and rights notice when available;
- label maps and reconstructions as such;
- do not treat artistic reconstruction as archaeological proof;
- do not upload, redistribute, or embed publisher assets unless the license and reuse terms permit it;
- when reuse is unclear, cite the resource for private preparation rather than copying it into a public artifact.

## Internal source record

When a licensed library contributes, record:

```yaml
licensed_library:
  available: true | false
  platform:
  resource:
  module:
  entry_page_or_section:
  evidence_role:
  exact_quote_status: verified | paraphrase_only | lead_only
  rights_or_distribution_note:
  artifact_use:
```

Reader-facing lessons should cite the work normally. Keep account state, local paths, search commands, and tool narration out of the public lesson.
