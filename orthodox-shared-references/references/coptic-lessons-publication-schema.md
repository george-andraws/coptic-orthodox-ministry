# Coptic Lessons Publication Schema

Use this schema for durable Coptic Orthodox lessons, Bible-study guides and related publication notes.

## Core frontmatter

Preserve existing good fields. Add or normalize grounded values only.

Common fields:
- `title`
- `type`: `lesson`, `chapter-study`, `overview`, `audit`, `moc`
- `publish`
- `book`
- `passages`
- `audience`
- `summary`
- `date`
- `updated`
- `tags`
- `fathers`
- `lectionary`
- `season`
- `feast`
- `hero`
- `audio`
- `deck`

Do not invent passages, Fathers, feast placement, lectionary placement, Psalm numbering, or publication status. Omit uncertain values and report them.

## Bible-study notes

- Use `type: chapter-study` for session guides.
- Use `Overview`, never `General Introduction`.
- Body normally begins after frontmatter with the reader-facing opening paragraph or first overview/passage section. Do not add `## Navigation` to guide bodies.
- For chapter-study / Bible-study structure, defer to [`bible-study-guide-structure-standard.md`](bible-study-guide-structure-standard.md): `## Spiritual Fruit 🍇` followed by sibling H2 `## Teaching Notes`, with plain passage labels and no knowledge-base heading links. Preserve an approved existing form during bounded revision unless structural migration is authorized. Optional teaching categories and approved passage-local lesson-guide boxes follow that standard, not a second schema here.
- Keep Bible-study organization broad enough for Pentateuch, Historical Books, Psalms, Wisdom, Prophets, Maccabees, Gospels, and New Testament projects.
- Schema compliance is required before a note is considered complete.

## Lesson notes

- Use `type: lesson` for adult-meeting, feast, fast, saint, and spiritual teaching notes.
- Derive `passages` from the body, not the title, unless the body confirms the governing passage.
- Add a complete, specific one-sentence `summary` suitable for cards and search. Check the target publication's preview truncation limit before batch drafting and keep summaries within it. Validate the actual formatted output, not only the raw YAML, because a grammatical source sentence can still be clipped on cards.

## Synaxarium commemoration

When commemoration is material to a lesson or overview, verify it against identified Synaxarium or liturgical sources and record the edition or version checked. Preserve confirmed, likely, uncertain and absent-evidence distinctions internally and qualify reader claims where necessary. Include substantive verified commemoration material when it helps, under an appropriate section or within the existing explanation. A likely lead alone does not require a new heading. Record an unconfirmed search in editorial evidence by default; add a brief reader-facing limitation only to prevent a likely false inference. Do not guess dates or add absence apparatus solely to demonstrate research.

## Formatting rules

- Use three spaces for nested bullets under numbered lists when preserving Markdown list hierarchy.
- Translation/source notes must name the text source without machinery: `Embedded Scripture is from Brenton's English Septuagint (LXX).`
- Do not mention scripts, commands, helpers, local file paths, extraction tooling, file sizes, model names, TODOs, placeholders, citation-needed markers, or speech-generation annotations in reader-facing notes.
- Embedded icon, map, or manuscript image source captions use exactly: `<small><em>Source: [name or work], [license or URL]</em></small>`.
