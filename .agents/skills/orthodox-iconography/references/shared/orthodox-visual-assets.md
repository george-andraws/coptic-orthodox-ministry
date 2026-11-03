# Orthodox Visual Assets

Use visual material when it clarifies teaching, not as decoration. Use this reference only when visual research, interpretation or assets are actually material and authorized. Prose-only revision and reviews that exclude visuals do not require new image searches or placeholders; preserve sound existing captions/rights unless their correction is in scope.

## Good assets

- Orthodox/Coptic/Byzantine icons
- maps of journeys, cities, battles, exile, or missionary routes
- manuscripts, museum objects, archaeological sites, churches, monasteries, landscapes, or artifacts
- public-domain, Creative Commons, museum, church, monastery, library, Wikimedia Commons, academic, or official-site sources

## Coptic and Orthodox iconography priority

For Bible-study iconography tasks, search Coptic, Coptic Orthodox, Oriental Orthodox, Egyptian Christian, Syriac, Armenian, and Ethiopian sources first when the passage/theme allows, then broaden to other Orthodox, Byzantine, Greek, Russian, Serbian, Macedonian, or related Eastern Christian styles.

It is acceptable to embed more than one Last Supper / Mystical Supper icon when each image adds a distinct theological, pastoral, or tradition-specific angle. Make Coptic/Egyptian material primary when it is available with clear rights. Use broader Orthodox styles as secondary witnesses, not replacements for available Coptic sources.

Prefer clearly licensed or public-domain assets for embedded local copies. If a modern icon print, church page, or commercial source has unclear rights, use it only as a reference link or inspiration unless reuse permission is explicit.

## Current online icon and visual-source search standard

Do not rely only on old cached project manifests or generic Wikimedia category pages. For new Bible-study final revisions, lesson drafts, Gospel visual passes, and iconography audits, do a current online source check when visuals would materially deepen the guide.

Use this search order:

1. **Coptic and Egyptian Christian sources first:** CopticIconography.com, Coptic church and monastery galleries, named Coptic iconographer portfolios, UK Coptic Icons / Neo-Coptic iconography resources, and official parish pages with icon explanations.
2. **Open academic and archival sources:** Manar al-Athar, museum collections, libraries, academic photo archives, manuscript repositories, archaeological site pages, and university resources.
3. **Wikimedia Commons individual file pages:** use file-level metadata, not category pages, and verify license, creator, source, MIME type, dimensions, and URL health before embedding.
4. **Broader Orthodox / Byzantine / Eastern Christian sources:** Greek, Russian, Serbian, Syriac, Armenian, Ethiopian, monastery, and icon-studio pages, clearly labeled by tradition.
5. **Western biblical art only when it teaches a real narrative, emotional, geographic, or historical point and is labeled as Western art, not iconography.**

Recent Coptic iconography articles can be valuable because they often explain the theological program of a contemporary church icon cycle, such as Pantocrator, Transfiguration, Anastasis, Virgin of the Sign, Good Shepherd, Crucifixion, Nativity, or sanctuary imagery. Use these as interpretation and source leads, but do not embed modern copyrighted images as reusable assets unless rights are explicit.

For every selected visual, record: source page, creator or owner when known, tradition/style, license or rights note, why it fits this passage, and whether it is embedded, linked only, or deferred for editorial review.

## Inline requirement

When a guide or lesson discusses an icon, map, manuscript, museum object, site, or artifact, include either:
- a standard Markdown image link such as `![alt](assets/file.jpg)` for a project-relative asset;
- a Markdown image URL such as `![alt](https://...)`, or
- a clear source link with attribution and rights/license note if embedding is not appropriate.

Place the image/link near the relevant explanation, in `Iconography Connection 🖼️` or `Iconography and Visual Teaching 🖼️`, or in a clear image/map/source subsection. The body and iconography sections describe what the image is and what it means. Teaching-use directions belong only in the final `## Spiritual Fruit 🍇` followed by sibling H2 `## Teaching Notes`, using a plain passage label and an optional Show category in accordance with the adopted structure standard.

## Source captions

When an embedded icon, map, manuscript image, museum image, or similar visual asset has a source line, put the source on the line directly below the image using exactly this smaller italic form:

`<small><em>Source: [name or work], [license or URL]</em></small>`

The caption is attribution only. Do not put teaching instructions, slide directions, or handout directions in the caption.

## Teaching Notes ownership

For Bible-study notes, every visual teaching instruction goes in the bottom `## Teaching Notes` section immediately after `## Spiritual Fruit 🍇`, using a plain passage label:

```markdown
## Spiritual Fruit 🍇

<Reader-facing spiritual fruit and practical application.>

## Teaching Notes

### The Letter to Artaxerxes (Ezra 4:11-16)
- Show: Use the embedded Achaemenid Empire map when explaining why the accusation against Jerusalem mattered politically.
```

Do not put lines like "use this map for a slide," "show students," or "for a handout" in the body, iconography section, or caption. Keep teaching-note headings as plain passage labels rather than application-specific links.

## Generated diagram revision and verification

1. Read the artwork's visible labels, not just its caption. Replace embedded teacher directions with reader-facing explanations and move instructional material to Teaching Notes. Compare embedded biblical wording with the adopted edition as carefully as guide prose; changing the surrounding caption does not repair an erroneous label inside the image. Keep substantive teaching available in adjacent page text and meaningful image alt text; SVG `<title>` and `<desc>` can supplement these but do not establish accessibility through every embedding method.
2. Check the diagram's argument before polishing its appearance. Distinguish sequence from genealogy, history from Christian fulfillment, and alternatives from causal steps. Remove a connecting arrow when it implies a false theological progression; a caption cannot reliably undo that visual claim.
3. Render each edited SVG with a suitable SVG renderer and inspect the actual image at readable resolution. Check every box, footer, long label, and curved path. Set `fill:none` on open connecting paths; SVG's default fill can turn a curved connector into an unintended solid wedge. Keep arrowhead fills explicit.
4. Fit the longest labels within their boxes by adjusting wording, line breaks, box size, or font size without sacrificing comfortable reading. Use a contact sheet to compare a batch, then inspect dense diagrams and suspect labels at readable individual-image scale; a downscaled sheet cannot prove small-text legibility. Shorten explanatory footers before shrinking their fonts, while preserving the teaching point. Rerender and reinspect each corrected asset; inspecting the previous PNG does not verify the final SVG.
5. Measure text/background contrast using the actual fill colors. An opaque image keeps its internal palette on either page theme, so explain that distinction rather than claiming a dark-mode page test that was not performed. Verify the surrounding rendered page separately when theme integration is in scope.

## Cautions

- Distinguish icons from illustrative images.
- Do not invent iconographic details.
- Use `orthodox-iconography` when visual theology or icon identification matters.
- If rights are unclear, do not imply free reuse. Provide source, owner/creator when known, and rights note.
- Verification should warn about missing images when the text mentions icons/maps/manuscripts, but missing images should not automatically block theological completion.
