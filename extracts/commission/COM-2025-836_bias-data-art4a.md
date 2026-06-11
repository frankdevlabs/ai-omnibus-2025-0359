# COM(2025) 836 — Special-category data for bias detection (new Article 4a; Article 10 of the AI Act)

> Source: **COM(2025) 836 final**, 19 November 2025 — interinstitutional file **2025/0359 (COD)**.
> Working transcription, not an official text — verify against the authoritative document
> (EUR-Lex CELEX 52025PC0836; committed PDF under [`../../sources/commission/`](../../sources/commission/)).
> Agreed-text counterpart: [`../agreed/PE-789081_bias-data-art4a.md`](../agreed/PE-789081_bias-data-art4a.md).
> See [`../../NOTICE`](../../NOTICE).

**Covers:** Article 1, points **(5)** and **(7)** of the proposal. Rationale: [recital (6)](./COM-2025-836_recitals.md#recital-6).
Analysis: [`../../docs/provisions/bias-data-art4a.md`](../../docs/provisions/bias-data-art4a.md).

---

<a id="point-5--article-4a-bias-data"></a>
## Point (5) — new Article 4a inserted (processing of special categories of personal data)

(5) the following Article 4a is inserted in Chapter I:

> ‘**Article 4a**
>
> **Processing of special categories of personal data for bias detection and mitigation**
>
> 1. To the extent necessary to ensure bias detection and correction in relation to high-risk AI systems in accordance with Article 10 (2), points (f) and (g), of this Regulation, providers of such systems may exceptionally process special categories of personal data, subject to appropriate safeguards for the fundamental rights and freedoms of natural persons. In addition to the safeguards set out in Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680, as applicable, all the following conditions shall be met in order for such processing to occur:
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
> (f) the records of processing activities pursuant to Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680 include the reasons why the processing of special categories of personal data was necessary to detect and correct biases, and why that objective could not be achieved by processing other data.
>
> 2. Paragraph 1 may apply to providers and deployers of other AI systems and models and deployers of high-risk AI systems where necessary and proportionate if the processing occurs for the purposes set out therein and provided that the conditions set out under the safeguards set out in this paragraph.;

*Transcription notes (not source text): (i) "Article 10 (2)" carries a space before "(2)" in the source; (ii) paragraph 2's closing clause — "provided that the conditions set out under the safeguards set out in this paragraph" — is garbled/incomplete in the source and is reproduced as printed; (iii) the inserted text ends ".;" with no closing quote mark.*

▸ Lifts the special-category-data processing basis out of current Article 10(5) AI Act (which is limited to providers of high-risk systems) into a new free-standing Article 4a in Chapter I, with a revised safeguard list, and extends it (paragraph 2) to providers and deployers of **all** AI systems and models and to deployers of high-risk systems. The "strict necessity" wording of current Article 10(5) becomes "To the extent necessary".

---

<a id="point-7--article-10-data-governance"></a>
## Point (7) — Article 10 amended (data and data governance)

(7) Article 10 is amended as follows:

(a) paragraph 1 is replaced by the following:

> ‘1. High-risk AI systems which make use of techniques involving the training of AI models with data shall be developed on the basis of training, validation and testing data sets that meet the quality criteria referred to in paragraphs 2, 3 and 4 of this Article and in Article 4a(1) whenever such data sets are used.’;

(b) paragraph 5 is deleted;

(c) paragraph 6 is replaced by the following:

> ‘6. For the development of high-risk AI systems not using techniques involving the training of AI models, paragraphs 2, 3 and 4 of this Article and Article 4a(1) shall apply only to the testing data sets.’;

▸ Consequential to [point (5)](#point-5--article-4a-bias-data): deletes Article 10(5) (the current in-article special-category-data basis) and re-points the Article 10 data-quality criteria to the new Article 4a(1).

---
Slices: [tracker.yaml `extract_slices`](../../tracker.yaml) · sibling files in this directory share the same structure.
