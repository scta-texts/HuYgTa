# Spot-Check Report — Augustine De Trinitate Quotes

Encoding session reports for `augustinedetrinitate_candidates_for_HuYgTa.json`.
Check items off as you verify them. Line numbers were current when each batch was written;
if a link is off, grep for the `source="...@range"` attribute, which is stable.

## Batch 1 (2026-07-16) — 10 candidates: 3 encoded (4 quote elements), 7 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Quamquam de illo igne disceptari potest, vtrum oculis, an spiritu visus sit" (Augu. 2. de trin.) | `adt-l2-d1e235@10-24` | [e52807:458](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-e52807/cod-TxxxqU_HuYgTa-e52807.xml:458) |
| <ul><li>[ ] </li></ul> | 2 | "Non enim viderunt linguas velut ignem… non solet dici, usum est mihi, sed vidi" (Augu. 2. de trin. — same paragraph, second Augustine citation) | `adt-l2-d1e235@25-83` | [e52807:463](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-e52807/cod-TxxxqU_HuYgTa-e52807.xml:463) |
| <ul><li>[ ] </li></ul> | 3 | "omnes, qui ante eum scripserunt de trinitate… vnius diuinae substantiae" (August. 1. de trini) | `adt-l1-d1e36@1-34` | [d1e304:881](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-d1e304/cod-TxxxqU_HuYgTa-d1e304.xml:881) |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — HuYgTa-e52807-d1e331 / adt-l2-d1e213 — MS quotes Gal 4:4 ("dicit Apostolus, Misit Deus filium suum factum ex muliere"); adt-l2 also cites same scripture. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 5 | **not_found** — HuYgTa-159627-d1e1451 / adt-l13-d1e1387 — MS cites John 1:12-13 ("iuxta illud, Quotquot autem receperunt eum"); adt-l13 contains same scripture. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 6 | "Neque enim diuinorum librorum tantummodo auctoritas… praestantissimum conditorem" (Augus. 15. de trin.) | `adt-l15-d1e1728@28-55` | [e24560:115](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-e24560/cod-TxxxqU_HuYgTa-e24560.xml:115) |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — HuYgTa-e49734-d1e1676 / adt-l13-d1e1460 — both MS and adt-l13 cite Rom 5:5; MS attribution is to book 15, not 13. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — HuYgTa-e49734-d1e1676 / adt-l8-d1e996 — both MS and adt-l8 cite Rom 5:5; MS attribution is to book 15, not 8. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — HuYgTa-e53889-d1e1266 / adt-l13-d1e1460 — MS uses "iuxta illud Caritas Dei diffusa est" (scripture citation only). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 10 | **not_found** — HuYgTa-e53889-d1e1266 / adt-l8-d1e996 — same paragraph, same reason as #9. No edit. | — | — |

### Notes
- **#1 & #2** (e52807-d1e878): Two distinct Augustine citations from the same adt-l2-d1e235 source, encoded as two separate `<quote>` elements. The MS explicitly labels them separately ("Vnde ait sic" / "subdit Augustinus"). Most worth checking: the second quote (@25-83) is a long passage spanning 7 lines.
- **#3** (d1e304-d1e1817): MS changes first-person ("ante me scripserunt") to third-person ("ante eum scripserunt") — a standard paraphrase. Range @1-34 covers the full parallel content.
- **#6** (e24560-d1e193): `<ref>` element for the citation was already present; only the `<quote>` element was added after the `</ref>`.
- **#7–#10**: Four not_found items all involve the same scripture verse (Rom 5:5 / "Caritas Dei diffusa est"). The HuYgTa-e49734-d1e1676 paragraph is already correctly encoded with adt-l15-d1e1902 and adt-l15-d1e1896 pointing to the actual book 15 Augustine text.
- **Auto-detected at session start**: 30 candidates already encoded in XML were reconciled automatically.

## Batch 2 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found** — e53889-d1e1266 / adt-l15-d1e1893 — MS cites scripture "iuxta illud Caritas Dei diffusa est" (Rom 5:5). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 2 | **not_found** — 159627-d1e1451 / adt-l13-d1e1406 — MS cites John 1:12-13 "iuxta illud, Quotquot autem receperunt eum"; adt-l13 opens with commentary on same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 3 | **not_found** — 303557-d1e452 / adt-l1-d1e169 — MS cites John 5:27-29 "vt patet, in loan vbi dicitur…Nolite mirari hoc"; adt-l1-d1e169 is Augustine's commentary on the same passage. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — d1e3XX-d1e873 / adt-l3-d1e463 — both cite Wisdom 9:16 "difficile inuestigamus ea quae in terris sunt"; no Augustine attribution in MS. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 5 | **not_found** — 133205-d1e1495 / adt-l13-d1e1495 — MS cites "Et ad Rom. 5. dicitur, Per unum hominem peccatum" (Rom 5:12); adt-l13-d1e1495 also cites same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 6 | **not_found** — 219385-d1e1394 / adt-l14-d1e1675 — MS cites "iuxta quod ait Apostolus" (2 Cor 3:18) and "beatus Ioannes" (1 John 3:2); adt-l14-d1e1675 quotes same scriptures. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — 126458-d1e713 / adt-l14-d1e1668 — MS cites "iuxta illud Apostoli, Nos autem reuelata facie gloriam domini speculantes" (2 Cor 3:18); adt-l14 also quotes this verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — 126458-d1e713 / adt-l15-d1e1769 — same paragraph and scripture (2 Cor 3:18) as #7. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — 193521-d1e336 / adt-l8-d1e968 — both cite 1 Tim 1:5 "finis praecepti est caritas"; no Augustine attribution in MS for this text. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 10 | **not_found** — d1e3XX-d1e502 / adt-l4-d1e637 — both cite Wisdom 9:10 "Mitte illam de sanctis caelis tuis"; MS separately cites "Aug. 8 de trinitate" for a different point. No edit. | — | — |

### Notes
- **Pattern emerging**: a large proportion of candidates at intersectionCount 7–10 are false positives driven by shared scripture citations (2 Cor 3:18, 1 John 3:2, Rom 5:12, Wisdom 9:10/16, John 5:27-29, Rom 5:5) rather than genuine Augustine quotations.
- All 10 in this batch were false positives — no XML edits required.

## Batch 3 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found** — d1e3XX-d1e615 / adt-l1-d1e59 — both cite Rom 11:33 ("O altitudo diuitiarum sapientiae et scientiae Dei"); MS attributes to "Apostolus". No edit. | — | — |
| <ul><li>[ ] </li></ul> | 2 | **not_found** — e2456X-d1e1757 / adt-l9-d1e1049 — MS cites "Augustinus I1. de Ciuitat. Dei" (De Civitate Dei, not De Trinitate); both works use same color/body accident analogy. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 3 | **not_found** — e49734-d1e1676 / adt-l7-d1e874 — paragraph already encoded; adt-l7 contains Rom 5:5. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — e52807-d1e331 / adt-l4-d1e627 — both cite Gal 4:4 ("misit deus filium suum factum ex muliere"); MS says "dicit Apostolus". No edit. | — | — |
| <ul><li>[ ] </li></ul> | 5 | **not_found** — e53889-d1e1266 / adt-l7-d1e874 — MS cites Rom 5:5 "iuxta illud Caritas Dei diffusa est"; adt-l7 contains same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 6 | **not_found** — 179720-d1e331 / adt-l1-d1e87 — MS is just "loannes ait. Cum apparuerit, similes ei erimus" (1 John 3:2); adt-l1 cites same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — 179720-d1e331 / adt-l12-d1e1366 — same paragraph, same scripture (1 John 3:2) as #6. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — 179720-d1e331 / adt-l14-d1e1672 — same paragraph, same scripture (1 John 3:2) as #6. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — 179720-d1e331 / adt-l2-d1e324 — same paragraph, same scripture (1 John 3:2) as #6. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 10 | **not_found** — 182071-d1e1104 / adt-l4-d1e583 — MS cites John 10:18 ("iuxta illud, quod ipse ait, Potestatem habeo ponendi animam meam"); adt-l4 also quotes same verse. No edit. | — | — |

### Notes
- **#2** worth a second look: MS cites "Augustinus I1. de Ciuitat. Dei" but the text match is with De Trinitate 9 (adt-l9-d1e1049). Could be a mis-citation in the MS; the phrase "non tamquam in subiecto ut color aut figura in corpore aut ulla alia qualitas" is a near-verbatim match.
- **179720-d1e331** (#6–9): This paragraph is extremely short ("Item, loannes ait. Cum apparuerit, similes ei erimus; quoniam videbimus eum, sicuti est") — purely a scripture citation (1 John 3:2), generating four false-positive candidate matches.
- Pattern continues: all intersectionCount-7 candidates in this batch are false positives driven by shared scripture citations.

## Batch 4 (2026-07-16) — 10 candidates: 1 encoded (1 quote element), 9 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found** — 185329-d1e1199 / adt-l2-d1e213 — MS cites Gal 4:4 ("secundum quod ait Apostolus, Misit Deus filium suum natum ex muliere"). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 2 | **not_found** — 295843-d1e462 / adt-l15-d1e1794 — MS cites Matt 15:17 ("auctoritate saluatoris, dicentis in euangelio, Omne quod in os intrat"); adt-l15 is Augustine's commentary on same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 3 | **not_found** — 315778-d1e2046 / adt-l1-d1e87 — MS cites 1 John 3:2 ("iuxta quod ait loan prima sua epistola, Cum apparuerit, similes ei erimus"). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — 315778-d1e2046 / adt-l12-d1e1366 — same paragraph, same scripture (1 John 3:2) as #3. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 5 | **not_found** — 315778-d1e2046 / adt-l14-d1e1672 — same paragraph, same scripture (1 John 3:2) as #3. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 6 | **not_found** — 315778-d1e2046 / adt-l2-d1e324 — same paragraph, same scripture (1 John 3:2) as #3. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — 324753-d1e3841 / adt-l1-d1e163 — MS cites Phil 2:9-10 ("vt ait Apost. ad Phila"); adt-l1-d1e163 also quotes same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 8 | "Humane mentis acies inualida, in tam excellenti luce figi non valet… nisi per iustitiam fidei nutrita vegetetur" (P. August. 1. de trin) | `adt-l1-d1e24@69-84` | [d1e3XX:114](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-d1e3XX/cod-TxxxqU_HuYgTa-d1e3XX.xml:114) |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — e19518-d1e570 / adt-l8-d1e996 — MS cites Rom 8:28 ("Scimus quoniam diligentibus Deum omnia cooperantur in bonum"); adt-l8 also quotes same verse. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 10 | **not_found** — e52807-d1e331 / adt-l1-d1e71 — MS cites Gal 4:4 ("dicit Apostolus, Misit Deus filium suum factum ex muliere"); adt-l1-d1e71 also quotes same verse. No edit. | — | — |

### Notes
- **#8** (d1e3XX-d1e111): Genuine quote, cleanly cited. A `<ref>` for the citation was already present in the XML; only the `<quote>` wrapper was added after it.
- **315778-d1e2046** (#3–6): Same pattern as 179720-d1e331 in batch 3 — four adt candidates all triggered by a single 1 John 3:2 citation in the MS.
- xmllint: pass.

## Batch 5 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | **not_found** — e52807-d1e433 / adt-l4-d1e577 — both cite Ps 18:5 ("in omnem terram exiit sonus eorum"). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 2 | **not_found** — e52807-d1e433 / adt-l4-d1e646 — same paragraph, same scripture (Ps 18:5). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 3 | **not_found** — 144414-d1e1135 / adt-l4-d1e580 — MS cites Rom 5:12 ("iuxta illud Apostoli, per unum hominem peccatum intrauit in mundum, & per peccatum mors"). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 4 | **not_found** — 149446-d1e2078 / adt-l4-d1e580 — same scripture (Rom 5:12) as #3, different paragraph. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 5 | **not_found** — 151635-d1e1474 / adt-l1-d1e49 — MS cites John 1:3 ("loan. 1. Omnia per ipsum facta sunt"); MS's Augustine citations are to "Aug. 9. super Gen" and "de sancta viduitate" (different works). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 6 | **not_found** — 151635-d1e1474 / adt-l13-d1e1387 — same paragraph, John 1:3 overlap only. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 7 | **not_found** — 151635-d1e1474 / adt-l13-d1e1390 — same paragraph, John 1:3 overlap only. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 8 | **not_found** — 151635-d1e1474 / adt-l4-d1e517 — same paragraph, John 1:3 overlap only. No edit. | — | — |
| <ul><li>[ ] </li></ul> | 9 | **not_found** — 159627-d1e1451 / adt-l13-d1e1454 — MS cites John 1:12-13 ("iuxta illud, Quotquot autem receperunt eum"). No edit. | — | — |
| <ul><li>[ ] </li></ul> | 10 | **not_found** — 183724-d1e1635 / adt-l1-d1e125 — MS cites Phil 2:8 ("Apostolus tangens Christi meritum ait, qui factus est obediens vsque ad mortem, mortem autem crucis"). No edit. | — | — |

### Notes
- **151635-d1e1474** (#5–8): MS paragraph cites John 1:3, "Aug. 9. super Gen", and "de sancta viduitate" — none of these are De Trinitate. Four adt candidates all triggered by the John 1:3 overlap.
- Running pattern: at intersectionCount 6, virtually all candidates are false positives driven by shared New Testament verses (John 1:3, John 1:12-13, Rom 5:12, Ps 18:5, Phil 2:8).

## Batch 6 (2026-07-16) — 10 candidates: 1 encoded (1 quote element), 9 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Deo supplicandum… essentia Veritatis" (MS: "Augustinus. 8. de trinitate in prooemio") | `adt-l8-d1e936@19-34` | [d1e3XX:263](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-d1e3XX/cod-TxxxqU_HuYgTa-d1e3XX.xml:263) |
| — | 2 | **not_found** — 183724-d1e1635 / adt-l1-d1e163: both cite Phil 2:8-9 (shared scripture) | — | no edit |
| — | 3 | **not_found** — 196854-d1e332 / adt-l4-d1e513: both cite 2 Cor 12:9 (shared scripture) | — | no edit |
| — | 4 | **not_found** — 199690-d1e675 / adt-l15-d1e1769: MS cites 2 Cor 3:18 ("iuxta quod ait Apostolus"); shared scripture | — | no edit |
| — | 5 | **not_found** — 212149-d1e1058 / adt-l2-d1e210: MS cites Wisdom 8:1 ("vt dicit Sapiens"); shared scripture | — | no edit |
| — | 6 | **not_found** — 212149-d1e1058 / adt-l3-d1e378: same paragraph as #5, same Wisdom 8:1 overlap | — | no edit |
| — | 7 | **not_found** — 219385-d1e1394 / adt-l15-d1e1769: MS cites 2 Cor 3:18 ("iuxta quod ait Apostolus"); shared scripture | — | no edit |
| — | 8 | **not_found** — 310842-d1e3222 / adt-l14-d1e1668: MS cites 2 Cor 3:18 ("ait Apo."); shared scripture | — | no edit |
| — | 9 | **not_found** — 310842-d1e3222 / adt-l15-d1e1769: same paragraph as #8, same 2 Cor 3:18 overlap | — | no edit |
| — | 10 | **not_found** — d1e3XX-d1e502 / adt-l2-d1e248: both cite 1 Tim 6:16 ("lucem inhabitat inaccessibilem"); shared scripture | — | no edit |

### Notes
- Row 1: MS omits the middle clause "et studium contentionis absumat" that appears in the De Trinitate source; the @19-34 range spans the full source passage including the omitted clause. Confirm whether partial omission warrants a narrower range.
- Rows 2–10: All false positives driven by shared scripture citations (Phil 2:8, 2 Cor 12:9, 2 Cor 3:18 ×4, Wisdom 8:1 ×2, 1 Tim 6:16). These paragraphs have no explicit Augustine attribution for the overlapping text.

## Batch 7 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| — | 1 | **not_found** — d1e964-d1e2379 / adt-l12-d1e1366: MS cites 1 John 3:2 directly ("iuxta illud Joan") and "August. in suis soliloquiis" (not De Trinitate) | — | no edit |
| — | 2 | **not_found** — d1e964-d1e2379 / adt-l14-d1e1672: adt-l14-d1e1672 also cites 1 John 3:2; shared scripture, no De Trinitate attribution | — | no edit |
| — | 3 | **not_found** — e21636-d1e1013 / adt-l15-d1e1991: MS is scholastic reply about love/spiratio; overlap on shared Trinitarian terminology; no Augustine citation | — | no edit |
| — | 4 | **not_found** — e21636-d1e1013 / adt-l6-d1e823: same paragraph; overlap on Trinitarian terminology; no Augustine citation | — | no edit |
| — | 5 | **not_found** — e21636-d1e1013 / adt-l7-d1e921: same paragraph; overlap on Trinitarian terminology; no Augustine citation | — | no edit |
| — | 6 | **not_found** — e29197-d1e355 / adt-l1-d1e90: MS has genuine De Trinitate cite ("nihil sit absurdius quam quod aliquid seipsum producat vt sit") but adt-l1-d1e90 does not contain this text; wrong candidate | — | no edit |
| — | 7 | **not_found** — e38481-d1e1370 / adt-l1-d1e14: MS cites Exodus 3:14 directly ("dixit ad Movsem. Ego sum, qui sum"); overlap on shared scripture/theological terms; no Augustine attribution | — | no edit |
| — | 8 | **not_found** — e38481-d1e1370 / adt-l1-d1e87: adt-l1-d1e87 also cites Exodus 3:14; shared scripture, no De Trinitate attribution in MS | — | no edit |
| — | 9 | **not_found** — e38481-d1e1370 / adt-l5-d1e680: adt-l5-d1e680 also cites Exodus 3:14; shared scripture, no De Trinitate attribution in MS | — | no edit |
| — | 10 | **not_found** — e38481-d1e1370 / adt-l7-d1e902: overlap on shared substance/essence terminology; no De Trinitate attribution in MS | — | no edit |

### Notes
- **⚠ Row 6 (e29197-d1e355)**: MS explicitly cites Augustine De Trinitate — "Augustinus t. de trin vult, quod nihil sit absurdius, quam quod aliquid seipsum producat vt sit" — but candidate adt-l1-d1e90 does not contain this text. The genuine quote exists somewhere else in De Trinitate; worth a manual search with `findTextCandidates` or `identifyReference` in a separate pass.
- Rows 1–2: MS paragraph d1e964-d1e2379 cites "August. in suis soliloquiis" (Soliloquies) and "Dyoni de diuinis nominibus" — not De Trinitate candidates.
- Rows 3–5: MS paragraph e21636-d1e1013 is pure scholastic disputation with no patristic attribution; Trinitarian terminology generates multiple spurious matches.
- Rows 7–10: MS paragraph e38481-d1e1370 cites Exodus 3:14 directly; this verse is quoted in several De Trinitate passages, driving four spurious matches.

## Batch 8 (2026-07-16) — 10 candidates: 1 encoded (1 quote element), 9 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| — | 1 | **not_found** — e45050-d1e700 / adt-l2-d1e201: both cite Phil 2:7 and John 16:14 ("Ipse me clarificabit: quia de meo accipiet"); shared scripture, no Augustine attribution | — | no edit |
| — | 2 | **not_found** — 127224-d1e469 / adt-l7-d1e870: MS cites John 5:26 directly ("Saluator dit in Ioanne, sicut pater habet vitam in semetipso"); shared scripture | — | no edit |
| <ul><li>[x] </li></ul> | 3 | "Qui habet caritatem magis nouit dilectionem, qua diligit, quam fratrem, quem diligit" (MS: "Augustinum, qui s[8] de tri[nitate] ait") | `adt-l8-d1e1003@13-22` | [141101:303](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-141101/cod-TxxxqU_HuYgTa-141101.xml:303) |
| — | 4 | **not_found** — 142805-d1e501 / adt-l7-d1e874: MS cites Gregorius and Rom 5:5 ("caritas diffusa in cordibus per spiritum sanctum"); no Augustine De Trinitate attribution | — | no edit |
| — | 5 | **not_found** — 146038-d1e799 / adt-l15-d1e1962: MS cites "Augustini in libro de fi. ad Petrum" (De fide ad Petrum, not De Trinitate); shared Trinitarian baptismal formula | — | no edit |
| — | 6 | **not_found** — 146038-d1e799 / adt-l15-d1e1991: same paragraph; MS cites De fide ad Petrum; overlap on "in nomine patris et filij et spiritus sancti" | — | no edit |
| — | 7 | **not_found** — 178612-d1e695 / adt-l13-d1e1387: MS cites John 1:14 directly ("Vidimus gloriam eius... pleni gratiae & veritatis"); shared Johannine prologue citation | — | no edit |
| — | 8 | **not_found** — 178612-d1e695 / adt-l13-d1e1504: same paragraph; Verbum/Word terminology overlap; no Augustine attribution | — | no edit |
| — | 9 | **not_found** — 179720-d1e331 / adt-l1-d1e176: MS cites 1 John 3:2 directly ("Ioannes ait. Cum apparuerit, similes ei erimus"); shared scripture | — | no edit |
| — | 10 | **not_found** — 179720-d1e331 / adt-l14-d1e1675: same paragraph; adt-l14-d1e1675 also cites 1 John 3:2; shared scripture | — | no edit |

### Notes
- Row 3: MS abbreviates book number as "s" (= 8) in "qui s de tri ait" — likely a scribal abbreviation for the numeral. Quote begins immediately after "ait." MS introduces with "Qui habet caritatem" which is a loose paraphrase of the broader context; the exact adt text for @13-22 is "magis enim nouit dilectionem qua diligit quam fratrem quem diligit."
- Rows 5–6: MS cites *De fide ad Petrum*, which generates spurious De Trinitate candidates because both share the baptismal Trinitarian formula.
- Rows 9–10: MS paragraph 179720-d1e331 is a bare scripture citation (1 John 3:2) with no surrounding text — generates repeated false positives (cf. batch 3).

## Batch 9 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| — | 1 | **not_found** — 179720-d1e331 / adt-l15-d1e1772: bare 1 John 3:2 citation; no Augustine attribution; adt-l15-d1e1772 is about 2 Cor 3:18 "speculantes" | — | no edit |
| — | 2 | **not_found** — 179720-d1e331 / adt-l4-d1e526: same paragraph; bare 1 John 3:2; overlap on general eschatological/Christological terms | — | no edit |
| — | 3 | **not_found** — 185329-d1e886 / adt-l13-d1e1460: MS cites Rom 5:8, John 3:16, 1 Pet 2:21, 1 Cor 6:20 directly; no Augustine De Trinitate attribution | — | no edit |
| — | 4 | **not_found** — 185329-d1e886 / adt-l13-d1e1495: same paragraph; both discuss Christ's death/redemption; shared scripture | — | no edit |
| — | 5 | **not_found** — 185329-d1e886 / adt-l4-d1e513: same paragraph; dilectio/caritas thematic overlap; no Augustine citation | — | no edit |
| — | 6 | **not_found** — 199690-d1e675 / adt-l14-d1e1668: MS cites 2 Cor 3:18 as "ait Apostolus"; no Augustine De Trinitate attribution (same paragraph seen in batch 6) | — | no edit |
| — | 7 | **not_found** — 207983-d1e1700 / adt-l15-d1e1962: MS cites Matt 28:19 and John 3:5 directly; Trinitarian baptismal formula overlap | — | no edit |
| — | 8 | **not_found** — 207983-d1e1700 / adt-l15-d1e1991: adt-l15-d1e1991 opens with Matt 28:19; shared scripture; no Augustine attribution | — | no edit |
| — | 9 | **not_found** — 213806-d1e1082 / adt-l15-d1e1962: MS discusses baptismal formula "in nomine patris et filij et spiritus sancti"; Trinitarian formula overlap | — | no edit |
| — | 10 | **not_found** — 213806-d1e1082 / adt-l15-d1e1991: same paragraph; same Trinitarian baptismal formula driver | — | no edit |

### Notes
- Rows 1–2: 179720-d1e331 is a single-verse MS paragraph (1 John 3:2 only) continuing to generate false positives across multiple batches — all remaining candidates for it will be false positives.
- Rows 3–5: 185329-d1e886 cites five different scriptures directly (Rom 5:8, John 3:16, 1 Pet 2:21, 1 Cor 6:20) with no patristic attribution; yields three spurious De Trinitate candidate matches.
- Rows 7–10: Two paragraphs (207983-d1e1700 and 213806-d1e1082) both discuss baptism using the Trinitarian formula; adt-l15-d1e1991 (De Trinitate closing prayer) also contains Matt 28:19, driving repeated false positives.

## Batch 10 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| — | 1 | **not_found** — 213806-d1e1642 / adt-l15-d1e1756: MS discusses valid baptism formulas; Trinitarian terminology overlap; no Augustine De Trinitate attribution | — | no edit |
| — | 2 | **not_found** — 213806-d1e1642 / adt-l15-d1e1962: same paragraph; Trinitarian formula overlap | — | no edit |
| — | 3 | **not_found** — 213806-d1e1642 / adt-l15-d1e1991: same paragraph; adt-l15-d1e1991 contains Matt 28:19; shared Trinitarian formula | — | no edit |
| — | 4 | **not_found** — 217436-d1e393 / adt-l15-d1e1962: MS cites "Augustinus ad Orosium" (different work, not De Trinitate); Trinitarian formula overlap | — | no edit |
| — | 5 | **not_found** — 217436-d1e393 / adt-l15-d1e1991: same paragraph; wrong Augustine work ("Ad Orosium") | — | no edit |
| — | 6 | **not_found** — 217436-d1e638 / adt-l15-d1e1962: baptism discussion; Trinitarian formula overlap; no Augustine attribution | — | no edit |
| — | 7 | **not_found** — 217436-d1e638 / adt-l15-d1e1991: same paragraph; shared Trinitarian formula | — | no edit |
| — | 8 | **not_found** — 219385-d1e1394 / adt-l1-d1e176: MS cites 1 John 3:2 as "beatus Ioannes ait"; shared scripture | — | no edit |
| — | 9 | **not_found** — 219385-d1e1394 / adt-l1-d1e87: same paragraph; MS cites 1 John 3:2 directly; shared scripture | — | no edit |
| — | 10 | **not_found** — 219385-d1e1394 / adt-l12-d1e1309: MS cites 2 Cor 3:18 as "ait Apostolus" and 1 John 3:2 directly; shared image/similitude theme | — | no edit |

### Notes
- Rows 1–3: Third distinct baptism-discussion paragraph from dir 213806, all generating spurious De Trinitate matches via Trinitarian formula.
- Rows 4–5: MS 217436-d1e393 cites Augustine but to "Ad Orosium" not De Trinitate — wrong work entirely.
- Rows 8–10: 219385-d1e1394 cites both 2 Cor 3:18 and 1 John 3:2 as explicit Apostle/John citations, generating three different candidate matches.

## Batch 11 (2026-07-16) — 10 candidates: 0 encoded, 10 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| — | 1 | **not_found** — 219385-d1e1394 / adt-l12-d1e1366: MS cites 2 Cor 3:18 + 1 John 3:2 as scripture; adt-l12-d1e1366 cites 1 Cor 13:12; all shared scripture | — | no edit |
| — | 2 | **not_found** — 219385-d1e1394 / adt-l14-d1e1668: same paragraph; image/similitude theme overlap; no Augustine attribution | — | no edit |
| — | 3 | **not_found** — 219385-d1e1394 / adt-l14-d1e1672: same paragraph; adt-l14-d1e1672 cites 1 John 3:2; shared scripture | — | no edit |
| — | 4 | **not_found** — 219385-d1e1394 / adt-l15-d1e1772: same paragraph; adt-l15-d1e1772 discusses 2 Cor 3:18 "speculantes"; shared scripture | — | no edit |
| — | 5 | **not_found** — 219385-d1e1394 / adt-l2-d1e324: same paragraph; Phil 2:6 / Christological terms overlap | — | no edit |
| — | 6 | **not_found** — 219385-d1e1394 / adt-l4-d1e526: same paragraph; body/soul mortality terms; no Augustine attribution | — | no edit |
| — | 7 | **not_found** — 227309-d1e2879 / adt-l12-d1e1366: MS cites 1 Cor 13:12 as "Apostolus" ("Nunc videmus per speculum & in aenigmate"); adt-l12-d1e1366 also cites 1 Cor 13:12; shared scripture | — | no edit |
| — | 8 | **not_found** — 253687-d1e854 / adt-l10-d1e1150: MS cites "Aug. in de ci. Dei" (De Civitate Dei, not De Trinitate); wrong Augustine work | — | no edit |
| — | 9 | **not_found** — 267439-d1e765 / adt-l15-d1e1962: MS discusses extreme unction with Trinitarian formula; no Augustine De Trinitate attribution | — | no edit |
| — | 10 | **not_found** — 267439-d1e765 / adt-l15-d1e1991: same paragraph; Trinitarian formula overlap | — | no edit |

### Notes
- Rows 1–6: 219385-d1e1394 has now exhausted all its candidates (9 total across batches 9–11); every one is a false positive driven by 2 Cor 3:18 and 1 John 3:2 scripture citations.
- Row 8: 253687-d1e854 cites Augustine explicitly but to *De Civitate Dei* — a recurring pattern where citing one Augustine work inflates intersectionCount against De Trinitate candidates via shared Augustinian vocabulary.

## Batches 12–20 (2026-07-16) — 92 candidates: 1 encoded (1 quote element), 91 not_found

| ✓ | # | Quote (MS citation) | Source | Link |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | 1 | "Nullum donum est illo dono excellentius, sola enim est quae diuidit inter filios regni aeterni, & filios perditionis aeternae" (MS: "Beati August. 15. de trin vbi louens de hoc dono spiritus sancti... sic ait") | `adt-l15-d1e1896@1-18` | [e49734:902](vscode://file/Users/jcwitt/Projects/scta/scta-texts/HuYgTa/HuYgTa-e49734/cod-TxxxqU_HuYgTa-e49734.xml:902) |
| — | 2–92 | **not_found** — see candidates JSON for individual notes | — | no edit |

### Notes
- Row 1 (batch 15): MS has "illo dono" where source has "isto dei dono" — minor variant form. Existing `<ref>` element for "Aug. 15. de trin" already present in paragraph; quote element added immediately after.
- **Genuine De Trinitate citations with wrong/missing candidate IDs** — worth follow-up:
  - **e29197-d1e355** (batch 7): MS "Augustinus t. de trin vult, quod nihil sit absurdius quam quod aliquid seipsum producat vt sit" — genuine but adt-l1-d1e90 doesn't match; search adt-l1 area
  - **e17419-d1e803** (batch 13): MS "Aug. 5. de tri." for "non sunt duo vel tria principia" — adt-l5-d1e756 doesn't match; search adt-l5
  - **e62745-d1e335** (batch 16): MS "Aug. 7. de tri." for "negat rationem speciei aut generis fore in diuinis" — adt-l7-d1e912 would match but wasn't listed as candidate
  - **126458-d1e600** (batch 17): MS "Beati Augus. 10. de tri." for "Nos sumus imago Dei, prout sumus filij Dei... in quo non est Iudaeus nec Graecus neque masculus neque femina" — adt-l3-d1e463 doesn't match; search adt-l10
- **Recurring false positive patterns identified across batches 12–20**:
  - Trinitarian baptismal formula "in nomine patris et filii et spiritus sancti" → adt-l15-d1e1991
  - 1 Cor 13:12 "Nunc videmus per speculum et in aenigmate" → adt-l12-d1e1366, adt-l14-d1e1668, adt-l15-d1e1772
  - Augustine De Doctrina Christiana 1 "Res quae nos beatos faciunt sunt pater et filius et spiritus sanctus" cited without work title — NOT De Trinitate
  - John 1:3 "Omnia per ipsum facta sunt" → adt-l13-d1e1387, adt-l13-d1e1390, adt-l4-d1e517
  - Wis 8:1 "Attingit a fine usque ad finem" → adt-l2-d1e210, adt-l3-d1e378
  - Gal 4:4 "misit Deus filium suum factum ex muliere" → adt-l2-d1e213, adt-l4-d1e627
  - Augustine De Civitate Dei citations → inflates intersectionCount against De Trinitate candidates

---

## Final Session Summary

**Total candidates processed: 242**
- Already encoded at session start (auto-detected): 30
- Newly encoded this session: 7
- Not found (false positives): 205

**Quotes encoded this session** (7 new `<quote>` elements):
1. e52807-d1e878 / adt-l2-d1e235 (2 quote elements, split passage)
2. d1e304-d1e1817 / adt-l1-d1e36
3. e24560-d1e193 / adt-l15-d1e1728
4. d1e3XX-d1e111 / adt-l1-d1e24
5. d1e3XX-d1e502 / adt-l8-d1e936
6. 141101-d1e621 / adt-l8-d1e1003
7. e49734-d1e1836 / adt-l15-d1e1896

**4 genuine De Trinitate citations remain un-encoded** (wrong candidate IDs in source data; see notes above).

---

## Follow-up: 4 Genuine De Trinitate Citations with Wrong Candidate IDs (2026-07-16)

These 4 paragraphs were flagged during batches 7–17 as having genuine De Trinitate citations but wrong candidate passage IDs. After targeted research, **none received `<quote>` elements** because the MS text is paraphrase or indirect speech, not verbatim quotation. The `<ref>` elements already present handle the citation markup correctly.

| ✓ | Para | MS Citation | Finding | Correct adt Source |
|---|---|---|---|---|
| <ul><li>[ ] </li></ul> | e29197-d1e355 | "Augustinus t. de trin **vult**, quod nihil sit absurdius, quam quod aliquid seipsum producat vt sit" | **Indirect speech** (`vult` + subjunctive = oratio obliqua); not a verbatim quote. No `<quote>` appropriate. No `<ref>` in XML. | adt book 1, specific passage not located |
| <ul><li>[ ] </li></ul> | e17419-d1e803 | "**ait** [Aug. 5. de tri.] quod sicut pater, & filius, & spiritus sanctus, non sunt duo, vel tria principia, **sic pari ratione non sunt duo, vel tres fines**" | `<ref>` already present. Source phrase "non duo uel tria principia" in **adt-l5-d1e750**, but "vel tres fines" is MS author's own extension. No verbatim quote to encode. | `adt-l5-d1e750` |
| <ul><li>[ ] </li></ul> | e62745-d1e335 | "contra [Aug. 7. de tri.] **vbi ipse negat** rationem speciei, aut generis fore in diuinis" | `<ref>` already present. Explicit paraphrase ("negat = he denies"), not a direct quote. | `adt-l7-d1e912` (about species/genus in Trinitarian predication) |
| <ul><li>[ ] </li></ul> | 126458-d1e600 | "[Beati Augus. **10**. de tri.] ... dicens. Nos sumus imago Dei, prout sumus filij Dei, & prout induimus Christum per fidem, in quo [Gal 3:28 already encoded]" | `<ref>` already present. MS cites **book 10** but content is from **adt-l12-d1e1331** (book 12 — likely MS book number error). "Nos sumus imago Dei, prout sumus filij Dei" is paraphrase of "efficimur etiam filii dei per baptismum Christi, et induentes nouum hominem Christum utique induimus per fidem." Gal 3:28 nested quote already encoded. No `<quote>` for the Augustine paraphrase. | `adt-l12-d1e1331` |

### Notes

- **e29197-d1e355**: The only case with no `<ref>` in the XML. MS author uses "vult" (maintains/wants) rather than "ait" (says), and the phrase "nihil sit absurdius... ut sit" uses subjunctive = oratio obliqua. This confirms paraphrase, not a direct quote. If a `<ref>` is wanted for this inline citation, it would need to be added manually with the correct adt-l1 passage.
- **126458-d1e600**: MS says book 10 but the argument (women and men equally made in God's image; Gal 3:28 as support) appears in **adt-l12**, not adt-l10. This is a genuine MS citation error on the book number. The `<ref>` (`HuYgTa-126458-Rd1e643`) already present points at the correct work (De Trinitate) but the wrong book.
- **Candidates JSON** has been updated with the correct adt source information in the `note` fields for all 4 entries.
