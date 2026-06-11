# Agreed-text extracts — working rules

> The extract set for **PE789.081** — the provisional agreement resulting from interinstitutional
> negotiations (13 May 2026, approved in IMCO/LIBE committee 2 Jun 2026 under Rule 75(4)) — lives
> here: one file per `tracker.yaml` `extract_slices` (`PE-789081_<slice>.md`), mirroring the
> [`../commission/`](../commission/) baseline so
> `git diff --no-index ../commission/COM-2025-836_<slice>.md PE-789081_<slice>.md` shows what the
> co-legislators changed. Source PDF:
> [`../../sources/parliament/`](../../sources/parliament/).
>
> **Caveat:** this text is a *provisional political agreement*, pending legal-linguistic revision,
> the plenary vote (indicative 15 Jun 2026) and Council adoption. Wording — including article
> numbering of new provisions — may still change. Until OJ publication the unamended AI Act
> 2024/1689 remains the law in force.

Before adding or editing any file in this directory, read
[`../commission/_TRANSCRIPTION_GUIDE.md`](../commission/_TRANSCRIPTION_GUIDE.md) and
[`../council/_TRANSCRIPTION_GUIDE.md`](../council/_TRANSCRIPTION_GUIDE.md) and follow them, with
these adaptations:

- PE789.081 prints the agreed text as **amendments to the Commission proposal** (EP-style: bold/italics
  markup in a single-column "Amendment" rendering). Transcribe the **consolidated agreed** operative
  text (markup applied), exactly as the Council guide prescribes for ST texts.
- Reuse the heading text and `<a id="...">` anchors from the matching `../commission/COM-2025-836_*`
  file wherever a point corresponds. Points added by the co-legislators (e.g. the Art 5 nudifier/CSAM
  prohibition) get their own heading + anchor in the same slug pattern.
- Mark whole-point deletions `[DELETED in PE789.081]`.
- Header block: source = **PE789.081** (CJ40_AG(2026)789081), 13 May 2026, interinstitutional file
  **2025/0359 (COD)**, "provisional agreement — working transcription, not an official text, pending
  legal-linguistic revision", and "See `../../NOTICE`."
- When the plenary adopts the first-reading position and/or the final act appears in the OJ, register
  the new document and diff it against this set; flag any divergence in `docs/what-changed.md`.
