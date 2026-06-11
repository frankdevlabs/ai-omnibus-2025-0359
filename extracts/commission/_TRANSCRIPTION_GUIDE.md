# Transcription guide for Commission base-text extracts

Internal standard for every file in `extracts/commission/`. The goal: a faithful, diffable
transcription of the **operative text of the Commission proposal COM(2025) 836 final** (CELEX
52025PC0836), structured to line up with the later text versions in `../agreed/` (and any
`../council/` sets) so that
`git diff --no-index ../commission/COM-2025-836_<slice>.md ../agreed/PE-789081_<slice>.md`
is meaningful.

## Source of truth
The committed proposal under `../../sources/commission/COM-2025-836_proposal_2025-11-19.pdf` (the
enacting articles and recitals), cross-checked against the authoritative EUR-Lex copy
(CELEX **52025PC0836**). Transcribe from the committed source on disk; never from memory or a web
summary.

## This is the baseline — there are no tracked changes
Unlike compromise texts, the Commission proposal is the **original**: there is nothing to
"consolidate". This is an **amending act**: Article 1 carries the AI Act (Regulation (EU) 2024/1689)
amendments as numbered points, Article 2 the aviation Regulation (EU) 2018/1139 amendments — *"In
Article 4, … is replaced by the following: …"*, *"the following Article 4a is inserted: …"*.
Transcribe those instructions and the **inserted/replacement operative text verbatim**, as the
proposal presents them. Use a `▸` change-note to flag what the proposal changes **versus the
pre-existing AI Act provision** (e.g. "replaces current Art 50(2) transition", "new conditional
application mechanism"), and — where it helps the reader — what the **co-legislators later did** to
that point, linking to the matching `../agreed/` anchor.

## Faithfulness rules (hard)
- Transcribe operative wording verbatim. This is primary legal text, not prose to paraphrase.
- Preserve the proposal's own numbering of amending points and of the inserted articles/paragraphs.
- Preserve bracketed placeholders exactly — e.g. `[OP: please insert the date = … following entry
  into force]` — that is *not* `[illegible]`; it is undecided in the source.
- If a passage is genuinely illegible/uncertain in the source, mark it `[illegible in source]` — never
  guess.

## Structure & anchors
- One file per slice in [`../../tracker.yaml`](../../tracker.yaml) `extract_slices`, named
  `COM-2025-836_<slice>.md`. The slices are THEME-based (the amending points grouped by the AI Act
  provisions they touch: literacy, prohibitions, classification, registration, transparency,
  sandboxes, governance, SMC, sectoral interaction, application dates, aviation, final provisions,
  recitals). Confirm the point-to-slice mapping against the text while transcribing and adjust
  `extract_slices` if the proposal's own structure fits better.
- Anchor every amending point with `<a id="point-N--article-X-topic"></a>` (recitals `recital-N`),
  so later versions can reuse the anchors and cross-version diffs line up. Where a later version
  deleted or replaced a point, keep it here with its own heading + anchor.
- Recitals file: curated subset (the contested/structural ones). State that it is a curated subset,
  not the full preamble.

## Header block (every file)
Open with a blockquote: source = **COM(2025) 836 final**, 19 Nov 2025, interinstitutional file
**2025/0359 (COD)**, "working transcription, not an official text", "verify against the
authoritative document (EUR-Lex CELEX 52025PC0836)", and "See `../../NOTICE`."

## Cross-links
Relative links only. Link the sibling extracts, the matching `../agreed/` anchors, and the relevant
`../../docs/provisions/*` / `../../docs/instruments/*` pages. Verify every internal link/anchor resolves
(`python3 ../../.claude/skills/transcribe-council-extract/linkcheck.py ../..`) before finishing.
