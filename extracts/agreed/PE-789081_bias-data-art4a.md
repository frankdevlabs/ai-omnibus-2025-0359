# PE789.081 — Special-category data for bias detection (new Article 4a; Articles 2(7) and 10 of the AI Act)

> Source: **PE789.081** (CJ40_AG(2026)789081) — provisional agreement resulting from
> interinstitutional negotiations, 13 May 2026 — interinstitutional file **2025/0359 (COD)**.
> Provisional agreement — working transcription, not an official text, pending legal-linguistic
> revision (committed PDF under [`../../sources/parliament/`](../../sources/parliament/)).
> The source prints clean consolidated agreed text (no EP amendment markup); transcribed as-is.
> Commission baseline counterpart: [`../commission/COM-2025-836_bias-data-art4a.md`](../commission/COM-2025-836_bias-data-art4a.md).
> See [`../../NOTICE`](../../NOTICE).

**Covers:** Article 1, points **(2b)**, **(5)** and **(7)** of the agreed text.
Rationale: [recital (6)](./PE-789081_recitals.md#recital-6).
Analysis: [`../../docs/provisions/bias-data-art4a.md`](../../docs/provisions/bias-data-art4a.md).
Mapping note: point (2b) (Article 2(7), data-protection interplay) is **new** — added by the
co-legislators; placed in this slice because its operative change is the new "without prejudice to
Article 4a and Article 59" carve-out anchoring the bias-data legal basis against the GDPR/LED
saving clause.

---

<a id="point-2b--article-2-7-data-protection"></a>
## Point (2b) — Article 2(7) replaced (interplay with Union data protection law)

(2b) paragraph 7 is replaced by the following:

> ‘7. Union law on the protection of personal data, privacy and the confidentiality of communications applies to personal data processed in connection with the rights and obligations laid down in this Regulation. This Regulation shall not affect Regulation (EU) 2016/679 or (EU) 2018/1725, or Directive 2002/58/EC or (EU) 2016/680, without prejudice to Article 4a and Article 59 of this Regulation.’

*Transcription notes (not source text): (i) the amending instruction does not name Article 2 — it follows point (2) ("Article 2 is amended as follows") yet is numbered as a free-standing point; (ii) the point sequence runs (2), (2b), (2c) — there is no point (2a) in the source.*

▸ **New — added by the co-legislators.** Updates the data-protection saving clause of current Article 2(7) AI Act: the existing "without prejudice to Article 10(5) and Article 59" becomes "without prejudice to **Article 4a** and Article 59", consequential to the relocation of the bias-data legal basis from Article 10(5) to the new Article 4a ([point (5)](#point-5--article-4a-bias-data); Article 10(5) is deleted by [point (7)](#point-7--article-10-data-governance)). The Commission proposal had left Article 2(7) untouched.

---

<a id="point-5--article-4a-bias-data"></a>
## Point (5) — new Article 4a inserted (processing of special categories of personal data)

(5) the following Article 4a is inserted in Chapter I:

> ‘**Article 4a**
>
> **Processing of special categories of personal data for bias detection and mitigation**
>
> 1. To the extent strictly necessary to ensure bias detection and correction in relation to high-risk AI systems in accordance with Article 10 (2), points (f) and (g), of this Regulation, providers of such systems may exceptionally process special categories of personal data, subject to appropriate safeguards for the fundamental rights and freedoms of natural persons. In addition to the provisions set out in Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680, as applicable, all the following conditions shall be met in order for such processing to occur:
>
> (a) the bias detection and correction cannot be effectively fulfilled by processing other data, including synthetic or anonymised data;
>
> (b) the special categories of personal data are subject to technical limitations on the re-use of the personal data, and state-of-the-art security and privacy-preserving measures, including pseudonymisation;
>
> (c) the special categories of personal data are subject to measures to ensure that the personal data processed are secured, protected, subject to suitable safeguards, including strict controls and documentation of the access, to avoid misuse and ensure that only authorised persons have access to those personal data with appropriate confidentiality obligations;
>
> (d) the special categories of personal data are not transmitted, transferred or otherwise accessed by other parties;
>
> (e) the special categories of personal data are deleted once the bias has been corrected or the personal data has reached the end of its retention period, whichever comes first;
>
> (f) the records of processing activities pursuant to Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680 include the reasons why the processing of special categories of personal data was strictly necessary to detect and correct biases, and why that objective could not be achieved by processing other data.
>
> 2. Providers and deployers of other AI systems and models and deployers of high-risk AI systems may exceptionally process special categories of personal data to the extent that:
>
> (a) processing is strictly necessary to ensure bias detection and correction in view of possible biases that are likely to affect the health and safety of persons, have a negative impact on fundamental rights or lead to discrimination prohibited under Union law, especially where data outputs influence inputs for future operations; and
>
> (b) all of the conditions and safeguards set out in paragraph 1 are applied.
>
> 2b. This paragraph does not create any obligation to conduct such bias detection and correction.’

*Transcription notes (not source text): (i) "Article 10 (2)" carries a space before "(2)" in the source, as in the Commission text; (ii) the final paragraph is numbered "2b." (not "3.") although no paragraph "2a" exists, and opens "This paragraph" where "This Article" may have been meant — as printed.*

▸ Reworks the Commission's [point (5)](../commission/COM-2025-836_bias-data-art4a.md#point-5--article-4a-bias-data): the **"strictly necessary"** standard of current Article 10(5) AI Act is **restored** in both paragraph 1 and the safeguard record-keeping condition (f) (the Commission had lowered it to "necessary"), and the extension to providers/deployers of other AI systems and models and deployers of high-risk systems (paragraph 2) is recast as an exceptional basis conditioned on likely effects on health and safety, fundamental rights or prohibited discrimination, with **all** paragraph-1 conditions and safeguards applying — replacing the Commission's garbled paragraph 2. New paragraph 2b confirms that the provision creates **no obligation** to conduct bias detection/correction. Per [recital (6)](./PE-789081_recitals.md#recital-6), Article 4a applies from the entry into application of this Regulation so that providers can prepare for the high-risk requirements.

---

<a id="point-7--article-10-data-governance"></a>
## Point (7) — Article 10 amended (data and data governance)

(7) Article 10 is amended as follows:

(a) paragraph 1 is replaced by the following:

> ‘1. High-risk AI systems which make use of techniques involving the training of AI models with data shall be developed on the basis of training, validation and testing data sets that meet the quality criteria referred to in paragraphs 2, 3 and 4 of this Article and in Article 4a(1) whenever such data sets are used.;’

(b) paragraph 5 is deleted;

(c) paragraph 6 is replaced by the following:

> ‘6. For the development of high-risk AI systems not using techniques involving the training of AI models, paragraphs 2, 3 and 4 of this Article and Article 4a(1) shall apply only to the testing data sets.;’

▸ Identical in substance to the Commission's [point (7)](../commission/COM-2025-836_bias-data-art4a.md#point-7--article-10-data-governance): deletes Article 10(5) (the current in-article special-category-data basis) and re-points the Article 10 data-quality criteria to the new Article 4a(1).

---
Slices: [tracker.yaml `extract_slices`](../../tracker.yaml) · sibling files in this directory share the same structure.
