---
name: coptic-orthodox-spiritual-lessons
description: Create and revise Coptic Orthodox spiritual lessons, adult-meeting lessons, feast and fast lessons, saint lessons, Orthodox articles, and church teaching notes.
---

# Coptic Orthodox Spiritual Lessons

Use this skill for Orthodox teaching artifacts: adult meeting lessons, Bible-study-style lessons, saint and Church Fathers sessions, feast/fast lessons, articles, reflections, WhatsApp promos, and servant teaching notes.

This skill is intentionally public and reusable. It must not depend on a private vault, local filesystem path, specific church calendar, or private source database.

## Lane discipline

- Use this skill for the full lesson artifact.
- Use `orthodox-biblical-explanation` for Scripture exegesis when the user asks mainly about a passage.
- Use `orthodox-iconography` when an icon, image, scene, inscription, or visual theology needs close interpretation.
- Use the shared references in `../shared-references/` for patristic sourcing, depth bar, source confidence, and visual asset policy.

## Core theological posture

All content must be:

- **Fully Orthodox.** Aligned with the Coptic Orthodox Church, the Church Fathers, and ancient Orthodox Christianity.
- **Christ-centered.** Every lesson should point to Christ: His person, His work, His Cross, His Resurrection, His Church.
- **Biblically grounded.** Scripture is primary. Use it richly, accurately, and in context.
- **Patristically informed.** Use real, verifiable patristic sources. Never invent quotes or attributions.
- **Sacramental and ecclesial.** Connect teaching to worship, prayer, fasting, feasts, repentance, Eucharist, Baptism, the Church, and the life of holiness where relevant.
- **Pastorally serious.** The lesson should move the heart toward repentance, faith, prayer, mercy, and transformation, not merely inform the mind.

Avoid:

- generic Christian content with Orthodox labels added afterward
- motivational or therapeutic content dressed up with Bible verses
- flattening Orthodox doctrine for broader appeal
- biography dumps that never become spiritual teaching
- doctrine lectures detached from prayer, repentance, worship, or the life of the Church

## Anti-filler rule

Every application must arise from the specific passage, doctrine, feast, fast, saint, icon, liturgical context, or pastoral burden being taught. Generic encouragement fails the quality bar.

Weak: "We should all be more faithful."

Stronger: "Because the blind man receives sight before he fully understands who Christ is, the lesson teaches us to obey the light we have received instead of waiting until every question is answered."

## Before drafting a full lesson

Unless the user explicitly says to draft immediately, begin with a short research-and-direction pass:

1. Identify the likely governing Scripture, feast, saint, doctrine, or pastoral burden.
2. Name the strongest lesson angle: theological burden, practical virtue, liturgical hook, or Church Fathers connection.
3. Ask only 2-4 clarifying questions that materially change the lesson.
4. Recommend a default direction if the user wants to proceed without answering.
5. Check whether iconography or visual material would deepen the lesson.

If the user asks for a quick announcement, promo, or short reflection, compress this step and proceed.

## Default full-lesson structure

Use this order for substantial lessons. Sections may be compressed, but do not silently omit the core safeguards.

1. **Title** - spiritually oriented, not merely descriptive.
2. **Main burden / core theme** - one paragraph naming the spiritual claim.
3. **Opening hook** - question, image, story, or contrast that exposes the need.
4. **Scriptural and historical context** - what is happening and why it matters.
5. **Main teaching sections** - work through the passage/topic in clean lesson prose.
6. **Christological anchor** - especially for lessons on virtue, ethics, mercy, justice, prayer, generosity, suffering, or repentance.
7. **Orthodox theological significance** - what the passage/topic reveals about Christ, salvation, the Church, theosis, repentance, worship, or the sacraments.
8. **Patristic insight** - real, sourced Fathers only. Prefer a few strong anchors over many decorative citations.
9. **Old Testament links and typology** - where genuinely relevant.
10. **Liturgical / sacramental / ecclesial connection** - connect to feasts, fasts, hymns, services, prayers, and sacraments when grounded.
11. **Iconography connection** - name and explain relevant icons or state briefly when no direct iconographic connection is central.
12. **Personal spiritual contemplation** - turn the teaching inward without sentimentality.
13. **Practical application for adult life** - concrete, non-generic, Monday-morning obedience.
14. **Conclusion** - return to Christ, not merely the hearer's effort.
15. **Teaching guide** - teacher-facing notes near the end, organized by passage or major section with plain section labels:
    - Ask: discussion prompt
    - Emphasize: teaching point
    - Watch for: pastoral caution or misunderstanding
    - Connect: link to Christ, repentance, worship, or the lesson arc
    - Show: when to use an icon, map, slide, or handout
16. **Discussion questions** - 3-5 if not already covered in the Teaching guide.
17. **Glossary / reference terms** - technical, patristic, historical, liturgical, Greek, Hebrew, Coptic, Syriac, or iconographic terms.
18. **Sources and further reading** - separate primary sources, secondary academic sources, Coptic Orthodox / pastoral sources, iconography/image sources, and web sources.
19. **Optional closing prayer**.

## Church Fathers and saint lessons

Do not teach saints as moral mascots or timelines. A strong Church Fathers lesson balances:

1. **Historical context** - upbringing, education, political/social/ecclesiastical climate, and why the moment mattered.
2. **Personal life and virtues** - formation, relationships, temptations, wounds, humility, courage, repentance, pastoral character.
3. **Doctrinal contribution** - what the saint taught or defended and why it mattered for salvation.
4. **Coptic/Orthodox reception** - Synaxarium, liturgical use, titles, common confusions, and the saint's continuing place in the Church.

If several saints share the same name, include a concise disambiguation table.

For Church Fathers lessons, include surviving works and legacy by genre rather than dumping titles. Explain why the writings mattered for worship, doctrine, Scripture reading, and spiritual life.

## Patristic sourcing rules

- Never fabricate a patristic quote.
- Prefer primary-source citations: work, book/chapter/section, homily number, or paragraph where possible.
- If exact wording is uncertain, paraphrase and say the Father teaches or emphasizes the theme rather than presenting quotation marks.
- If using a modern Coptic Orthodox source that summarizes the Fathers, cite it as a modern pastoral source, not as the ancient Father directly.
- Distinguish received liturgical attribution from modern historical certainty when needed.
- Use direct quotes sparingly and only when verified wording strengthens the teaching.

See `../shared-references/patristic-sources.md` and `../shared-references/source-confidence.md`.

## Liturgical and historical caution

If a rite, hymn, feast, reading, Synaxarium commemoration, or Coptic practice detail is uncertain, say so and verify. Do not guess.

When a traditional attribution or historical claim is contested, state it carefully:

- "The Church receives this text under..."
- "The exact history is more complex..."
- "This is a later tradition, but it expresses..."

## Visual and iconography guidance

Use iconography as theology in color, not decoration. For relevant lessons:

- name the icon or scene
- explain composition, figures, gestures, inscriptions, colors, placement, or symbols
- distinguish iconographic tradition from historical documentation
- cite image sources and rights where possible
- put teaching-use instructions in the final Teaching guide, not under the image caption

If an actual image must be identified, use `orthodox-iconography`.

## Short ministry announcements and promos

For announcements, WhatsApp promos, and short ministry communications:

- start with the spiritual foundation, not logistics
- name the service as obedience to Christ, not branding or activity
- give only the concrete details people need to trust and respond
- include specific ways to participate: pray, give, prepare, attend, invite, serve
- close with a clear invitation, not hedging

For outreach-specific messaging, use `orthodox-outreach-communications`.

## Output quality checklist

Before finalizing a lesson:

- Is the main burden clear?
- Is Christ central?
- Does the application arise from this specific material?
- Are patristic claims real and sourced?
- Are uncertain liturgical/historical claims marked honestly?
- Is the lesson Orthodox in imagination, not generic with Orthodox vocabulary?
- Does the Teaching guide help an actual servant teach the lesson?
