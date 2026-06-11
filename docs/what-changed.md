# What changed — full provision-by-provision diff

> The comprehensive companion to `STATUS.md`'s "What changed" summary — the **authority on what
> moved**. For every tracked provision it traces **current law → Commission proposal → agreed text
> (PE789.081)**, so it is clear *which institution changed what*. One row per provision in
> [`data/positions.csv`](../data/positions.csv).

Why this page exists: widely-reported "features of the proposal" are routinely added by
co-legislators (the Art 5 ban was never in the Commission text) or reversed in negotiation (three
Commission easements did not survive). And nothing here is law yet: **until OJ publication the
unamended AI Act 2024/1689 applies**.

**How to read each row.** The **provision** cell links to its analysis page in
[`provisions/`](provisions/); substantive cells end with a deep link into the operative text — the
**Commission** column into [`extracts/commission/`](../extracts/commission/), the **agreed** column
into [`extracts/agreed/`](../extracts/agreed/). State the **current-law baseline AND the proposal
separately**. Working transcriptions — **verify against the authoritative source**.

## AI Act (Regulation (EU) 2024/1689)

| Provision | Current law → Commission proposal | Agreed text (PE789.081, 13 May 2026) |
|---|---|---|
| [**High-risk dates (Art 6, Annexes I+III)**](provisions/high-risk-classification-and-dates.md) | *AI Act:* Annex III applies 2 Aug 2026, Annex I 2 Aug 2027. **Commission:** conditional mechanism tied to standards availability, backstop dates ("up to 16 months"). [Commission extract](../extracts/commission/COM-2025-836_application-dates.md) | **Fixed dates: Annex III → 2 Dec 2027, Annex I → 2 Aug 2028** (Council-mandate change). Safety-component definition narrowed. [Agreed extract](../extracts/agreed/PE-789081_application-dates.md) |
| [**Art 5 ban — nudifiers/CSAM**](provisions/prohibitions-art5-nudifiers-csam.md) | *Not in current law; NOT in the Commission proposal* | **New three-limb prohibition** (market-placement with purpose / without safeguards incl. "reasonably foreseeable and reproducible" provider limb / deployer use); applies **2 Dec 2026**; top fine band €35m / 7%. [Agreed extract](../extracts/agreed/PE-789081_prohibitions-art5.md) |
| [**AI literacy (Art 4)**](provisions/ai-literacy-art4.md) | *AI Act:* providers/deployers "ensure a sufficient level" (applies since 2 Feb 2025). **Commission:** replace with Commission/Member-State encouragement framework. [Commission extract](../extracts/commission/COM-2025-836_ai-literacy-art4.md) | Duty **restored on providers/deployers** at the lower *"take measures to support the development"* standard + no-guarantee clause + Commission/Member-State support duties (verified; pending legal-linguistic revision). [Agreed extract](../extracts/agreed/PE-789081_ai-literacy-art4.md) |
| [**Bias data (Art 10(5) / new Art 4a)**](provisions/bias-data-art4a.md) | *AI Act:* "strictly necessary", high-risk only. **Commission:** "necessary", all systems + deployers. [Commission extract](../extracts/commission/COM-2025-836_bias-data-art4a.md) | **"Strict necessity" restored**; beyond high-risk only by exception (health/safety/fundamental rights); no detection duty. [Agreed extract](../extracts/agreed/PE-789081_bias-data-art4a.md) |
| [**Registration (Art 49 / Annex VIII)**](provisions/registration-art49.md) | *AI Act:* self-assessed non-high-risk Annex III systems must register. **Commission:** scrap the duty. [Commission extract](../extracts/commission/COM-2025-836_registration-art49-annexviii.md) | **Restored** with simplified Annex VIII Section B requirements. [Agreed extract](../extracts/agreed/PE-789081_registration-art49-annexviii.md) |
| [**Watermarking (Art 50(2))**](provisions/transparency-art50-watermarking.md) | *AI Act:* applies 2 Aug 2026. **Commission:** 6-month grace to 2 Feb 2027 for systems already on the market. [Commission extract](../extracts/commission/COM-2025-836_transparency-art50.md) | **4-month transition to 2 Dec 2026**; other Art 50 duties unchanged from 2 Aug 2026. [Agreed extract](../extracts/agreed/PE-789081_transparency-art50.md) |
| [**Sandboxes / testing (Art 57)**](provisions/sandboxes-testing-art57.md) | *AI Act:* national sandbox by 2 Aug 2026. **Commission:** flexibility measures. [Commission extract](../extracts/commission/COM-2025-836_sandboxes-testing-art57.md) | National sandbox deadline → **2 Aug 2027**; real-world testing broadened to Annex I systems; possibility of an EU-level AI Office sandbox (Art 57(3a) — **no date in the text**, the "from 2028" in secondary reporting is not in PE789.081); post-market-monitoring flexibility. [Agreed extract](../extracts/agreed/PE-789081_sandboxes-testing-art57.md) |
| [**SME/SMC reliefs**](provisions/smc-simplifications.md) | *AI Act:* SME accommodations. **Commission:** extend simplified documentation/QMS. [Commission extract](../extracts/commission/COM-2025-836_smc-simplifications.md) | Extended to **small mid-caps** (definitions per Rec 2003/361/EC and Rec (EU) 2025/1099 in the operative text; "2025/3500/EC" appears only as a recital citation quirk). [Agreed extract](../extracts/agreed/PE-789081_smc-simplifications.md) |
| [**Annex I sectoral interaction**](provisions/sectoral-annexi-interaction.md) | *AI Act:* embedded AI under both AI Act + sectoral law. **Commission:** coherence adjustments. [Commission extract](../extracts/commission/COM-2025-836_sectoral-annexi-interaction.md) | **Machinery equivalence clause** removes double conformity; delegated/implementing-act empowerments for other sectors; operator-guidance duty. EP's Annex-I-Section-A deletion did **not** make it. [Agreed extract](../extracts/agreed/PE-789081_sectoral-annexi-interaction.md) |
| [**Governance / AI Office (Art 75)**](provisions/governance-aioffice-art75.md) | *AI Act:* AI Office supervises GPAI; national authorities supervise systems. | AI Office gains **partly exclusive competence** (same-provider GPAI systems; AI in VLOPs/VLOSEs) + investigation/inspection/commitment/fining tools; national authorities keep law enforcement, border, justice, financial institutions. [Agreed extract](../extracts/agreed/PE-789081_governance-aioffice-art75.md) |

## Aviation Regulation (EU) 2018/1139

| Provision | Current law → Commission proposal | Agreed text (PE789.081) |
|---|---|---|
| [**Art 2 omnibus — EASA framework**](provisions/aviation-reg-2018-1139.md) | *Reg 2018/1139:* no AI Act integration. **Commission:** technical integration of high-risk requirements. [Commission extract](../extracts/commission/COM-2025-836_aviation-reg-2018-1139.md) | Technical adjustments retained; low-controversy. [Agreed extract](../extracts/agreed/PE-789081_aviation-reg-2018-1139.md) |
