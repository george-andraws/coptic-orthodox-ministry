# Orthodox Artifact Production

Artifact production follows approved content unless an earlier draft asset is explicitly requested.

## Boundaries

- Do not create audio, slides, PDFs, shared documents, or publication packages from a weak draft unless a draft asset is explicitly requested.
- Keep approved Markdown as the source of truth unless the project specifies otherwise.
- Record downstream artifacts as stale when substantive source Markdown changes; distinguish freshness bookkeeping from permission to replace, detach, or regenerate them.

## Text-only revision with retained media

1. Before editing, inventory attached media, transcripts, and provenance records by file name, byte size, and checksum. Capture media links and identity metadata separately.
2. Check how the target publishing system represents retained but outdated media before changing freshness metadata. Preserve a supported metadata contract rather than introducing unverified fields.
3. Preserve media links, file names, recording identities, transcript references, and provenance records. Add a short reader-facing notice when a recording predates the text revision. Do not rewrite media or provenance records merely to make them appear current.
4. Verify inventoried file sizes and checksums against the baseline after the text revision, and compare identity metadata before and after. Report source freshness and unchanged media bytes as separate findings.
5. Where authorized, test the rendered result to confirm that the retained media and freshness notice appear correctly. If synchronization, building, or publication is excluded, respect that boundary and report only the verification actually performed.
