# Chapter 2 cold-start audit

Audit date: 2026-08-24
Target: flashcards/02_angle_relationships_and_parallel_lines.md
Mode: build, after approved chapter-1 pilot
Edge mode: explicit

## Frozen learner contract and chapter boundary

The machine-resolved inbound edge is only
chapter:01_geometric_language_and_measurement. The staged external deck closure
contributes arithmetic, measurement, and elementary variable/expression
capabilities; it does not contribute general equation solving, coordinate
geometry, slope, function graphs, or proof methods. No tool is assumed.

| Required boundary capability | Confirmed source | Use in chapter 2 | Status |
|---|---|---|---|
| Addition and subtraction of whole-number angle measures; inverse-operation checks | Staged mathematics/number-sense-and-arithmetic capability summary | Complementary/supplementary totals and missing measures | inbound |
| Variables, expressions, equality statements, substitution, and expression evaluation | Staged mathematics/elementary-algebra-and-functions capability summary | Reading measure equations such as \(m\angle 2=137^\circ\); no equation-solving procedure is required | inbound |
| Point, line, ray, segment, plane, endpoint, intersection, and line/ray notation | Chapter 1 cards f873cbb9-f8d6-4b33-8784-b48635055270 through 08a5f200-5cd4-4b75-b4bf-c2b5c16b6f35 | Intersections, opposite rays, parallel/perpendicular lines, and transversals | inbound |
| Angle, side, vertex, angle naming, \(m\angle ABC\), degree, right angle, and straight angle | Chapter 1 cards 41b16040-1e51-46a7-a190-cdf48bb4cc87 through 3d0e1f21-b396-496a-85a0-889d135985bb | Every angle-pair definition and computation | inbound |
| Square-corner and equal-angle marks; explicit marks override visual appearance | Chapter 1 cards 2a045052-1a70-47cc-af19-075a90b3bf1a through c22f64a9-f924-49b9-a469-88ea4b793c44 | Perpendicular marks, parallel-mark discrimination, and the unmarked-line counterexample | inbound |
| Construction and fixed relationships are exact in the ideal diagram | Chapter 1 cards b252c6e4-19ca-4a77-a0ef-ddd030059a70 through f01f837d-139d-457d-bc83-0ebe41848d44 | Meaning of a relationship established rather than guessed from appearance | inbound |

### Outbound capability ledger

| Provided capability | First explanation and supported retrieval | Faded or independent application | Status |
|---|---|---|---|
| angle-relationship | 61fdc768-44c7-418f-abe1-1de2b9432327 through ade972b2-13aa-4588-b871-85e6d373bb9d | 95eb21f7-a671-458f-911c-0039e771d38a | established |
| parallel-and-perpendicular-lines | a6286eae-80f4-45ce-92a9-ca6d79117ea6 through 656c9a13-5ae8-4ddb-b664-497d00ff62ea | 6e965c68-e5c4-4fae-a2b8-4000de32875a and 0b188993-1e19-4749-8907-d014996fce03 | established |
| transversal-angle-relationship | 95f0ca4f-3e11-4a79-baf5-b6d2922a23f3 through 22212e36-684c-4828-a44f-36a9ecb495c5 | 83ebb651-c754-4a92-8fd3-798f79c493c6, 09310030-c5e9-495f-a19c-c64e815c94dd, and 6e965c68-e5c4-4fae-a2b8-4000de32875a | established |
| short-geometric-argument | ade972b2-13aa-4588-b871-85e6d373bb9d, then explicit bridge 53ae7d60-2a52-43c0-90fd-4cc4a6ad02a0 | 0b188993-1e19-4749-8907-d014996fce03 | established |

No inbound edge was added. Rejected examples and methods: coordinate grids,
slope criteria, line equations, transformations, triangle facts, congruence
terminology, circle terminology, and formal proof layouts.

## Front-only cold-start scan

This pass was performed from an extraction containing card IDs and Q:/P:
fronts only. Answers and solutions were reviewed only after the dependency list
for every front had been recorded.

| # | Card ID | Dependencies needed to parse and attempt the front | Allowed source or earlier establishment | Status |
|---:|---|---|---|---|
| 1 | 61fdc768-44c7-418f-abe1-1de2b9432327 | angle, vertex, side; angle-region numbering; adjacent | Chapter 1; numbering and adjacent are minimally bridged on this front | pass |
| 2 | b78a1a7e-b065-49d4-b143-263e0922c135 | degree measure and addition; complementary | inbound arithmetic/Chapter 1; term bridged here | pass |
| 3 | 0c0ea388-87d0-4897-8133-b36b801ad730 | degree measure and addition; supplementary | inbound arithmetic/Chapter 1; term bridged here | pass |
| 4 | b90b44a5-2a71-4327-a608-fec853243d2a | adjacent versus complementary | cards 1–2 | pass |
| 5 | e0fb2dde-6775-4f06-a147-2c672d868cb2 | ray, endpoint, line, straight angle; opposite rays | Chapter 1; opposite rays bridged here | pass |
| 6 | b060df2a-ec56-4b7a-a2b1-9513178aa68f | adjacent, opposite rays, numbered regions; linear pair | cards 1 and 5; linear pair bridged here | pass |
| 7 | 02939ee5-03f4-484a-96c5-b22820d07633 | intersecting lines and numbered regions; vertical angles | Chapter 1/card 1; vertical angles bridged here | pass |
| 8 | ade972b2-13aa-4588-b871-85e6d373bb9d | vertical angles, adjacent angles, straight-angle total | cards 1, 3, 6–7 and Chapter 1 | pass |
| 9 | 95eb21f7-a671-458f-911c-0039e771d38a | linear pair, subtraction, angle-measure notation | cards 6–8 and inbound arithmetic | pass |
| 10 | a6286eae-80f4-45ce-92a9-ca6d79117ea6 | right angle and square mark; lowercase line labels; perpendicular and \(\perp\) | Chapter 1; label convention and relationship bridged here | pass |
| 11 | b5cfb198-4976-4018-bd9a-65eed4d1c1f3 | perpendicular, vertical equality, supplementary | cards 3, 8, 10 | pass |
| 12 | fff7cb6f-16ea-42fe-a104-f0159cd38f08 | plane and line; parallel, \(\parallel\), body marks | Chapter 1/card 10; all new items bridged here | pass |
| 13 | b4d61404-966f-42d3-98f5-b6f574fad5b5 | parallel body marks versus continuation arrowheads | card 12 and Chapter 1 line grammar | pass |
| 14 | 725869d3-24cc-4cbe-bea4-d0d304963aea | diagram appearance versus stated relationship | Chapter 1 diagram-evidence card and cards 12–13 | pass |
| 15 | 656c9a13-5ae8-4ddb-b664-497d00ff62ea | parallel versus perpendicular | cards 10–14 | pass |
| 16 | 95f0ca4f-3e11-4a79-baf5-b6d2922a23f3 | line intersection, line labels, numbered regions; transversal | Chapter 1/cards 1 and 10; transversal bridged here | pass |
| 17 | bc55aa4a-eeb5-409e-8b35-01f915c9c519 | transversal and between/outside regions; interior/exterior | card 16; terms bridged here | pass |
| 18 | 2b58054d-e00a-440b-ac1e-ef0a2dbbee62 | two transversal intersections; corresponding positions | cards 16–17; relationship bridged here | pass |
| 19 | 28ea426c-c386-42f6-b4c5-e8a9ba5ad88d | interior position and side of transversal; alternate interior | cards 16–17; relationship bridged here | pass |
| 20 | 9543f29b-78e0-47b9-a830-a3c7b3d0dc31 | exterior position and side of transversal; alternate exterior | cards 16–17; relationship bridged here | pass |
| 21 | cae65056-084e-4f56-876e-b87b77e0eafa | interior position and side of transversal; same-side interior | cards 16–17; relationship bridged here | pass |
| 22 | 11ceccba-d469-44b0-aa14-16ad8099f7de | parallel marks and all three equal-measure angle families | cards 12–13 and 18–20; result bridged here before retrieval | pass |
| 23 | 22212e36-684c-4828-a44f-36a9ecb495c5 | same-side interior and supplementary | cards 3, 12, 21; result bridged here | pass |
| 24 | d71aa177-2784-427b-866a-fb3cae8f877a | parallel condition for across-intersection results; local vertical result | cards 7–8 and 22–23 | pass |
| 25 | 83ebb651-c754-4a92-8fd3-798f79c493c6 | corresponding equality, degree measure, linear-pair check | cards 6, 18, 22 and inbound arithmetic | pass |
| 26 | 09310030-c5e9-495f-a19c-c64e815c94dd | alternate exterior equality, linear pair, two named relationships | cards 6, 20, 22 and problem 25 progression | pass |
| 27 | 0c9cf9ca-6ed3-455d-bbf8-ee1de1c22c3c | missing parallel evidence and corresponding equality condition | cards 14, 18, 22, 24 | pass |
| 28 | 6e965c68-e5c4-4fae-a2b8-4000de32875a | corresponding placement; reverse angle test | card 18; reverse test explicitly bridged on this front | pass |
| 29 | 53ae7d60-2a52-43c0-90fd-4cc4a6ad02a0 | perpendicular measures, corresponding positions, reverse test; short argument | cards 10–11, 18, 28; short-argument grammar bridged here | pass |
| 30 | 0b188993-1e19-4749-8907-d014996fce03 | square marks, transversal, corresponding measures, reverse test, reason-conclusion chain | cards 10–13, 16, 18, 28–29 | pass |

## Separate first-use scan

| First-use item | First front | Finding |
|---|---|---|
| Adjacent; nonoverlapping angle regions; angle-region numeral | card 1 | Definition and figure grammar precede use |
| Complementary and \(90^\circ\) total | card 2 | Definition precedes contrast/application |
| Supplementary and \(180^\circ\) total | card 3 | Definition precedes linear-pair use |
| Opposite rays | card 5 | Definition precedes linear-pair definition |
| Linear pair | card 6 | Adjacent and opposite rays already retrieved |
| Vertical angles and their equality | cards 7–8 | Position is retrieved before the reason is requested |
| Perpendicular, lowercase line label, and \(\perp\) | card 10 | Minimal bridge and square-marked retrieval share the front |
| Parallel, \(\parallel\), and parallel body marks | card 12 | Minimal bridge precedes mark discrimination |
| Transversal | card 16 | Line/intersection vocabulary is inbound |
| Interior/exterior and four transversal families | cards 17–21 | One family is introduced and retrieved per front |
| Equal/supplementary parallel-transversal results | cards 22–23 | Position families and the parallel condition are already established |
| Reverse corresponding-angle test | card 28 | Rule is stated before supported classification |
| Short reason-conclusion chain | card 29 | Analyzed vertical-angle reason and worked problems precede the explicit bridge |

No front, figure label, Markdown alt text, supplied premise, distractor, or
technical use of an ordinary word requires a later chapter. The detailed SVG
description for intersecting_lines was kept neutral so it does not reveal the
vertical-angle answer.

## Answer, solution, and structure audit

- All angle totals and subtractions were recomputed. The problem results are
  \(43^\circ\), \(68^\circ\), \(52^\circ\), a parallel-line conclusion from
  equal corresponding angles, and \(r\parallel s\).
- Every transversal equality explicitly requires stated or marked parallel
  lines. The unmarked look-alike rejects appearance as evidence.
- All five P:/S: cards begin S: with **IDENTIFY**, retain
  **PLAN → EXECUTE → EVALUATE** in order, and place the direct result as the
  first sentence of **EXECUTE**.
- Each **EVALUATE** stage uses an inverse total, an independent relationship
  chain, a necessary-position check, or a missing-premise test.
- No A: or S: body begins with a bare number and period.
- Card IDs are unique and new because the scaffold contained no scheduled
  chapter-2 cards.

## Inventory reconciliation

| Inventory | Planned | Actual | Reconciliation |
|---|---:|---:|---|
| Q:/A: | 25 | 25 | matched |
| C: | 0 | 0 | matched; exact insertion was not the best retrieval form |
| P:/S: | 5 | 5 | matched; completion → one-step → two-step → converse → independent argument |
| Figures | 6 | 6 | matched; angle-pair, intersection, line-mark, transversal-family, unmarked-condition, and perpendicular-to-one-line roles are distinct |

Intentionally omitted opportunities remain: decorative road/rail photographs,
tool remeasurement, exact parallel/perpendicular construction sequences,
coordinate/slope representations, triangles, transformations, and formal proof
layouts.

## Validation note

The final deck validation reported zero parser, KaTeX, image, identity, markup,
cloze, and frontmatter findings, and the stable-ID and generated-figure checks
passed. The CLI also reported one environment-level prerequisite error because
it searched for mathematics/elementary-algebra-and-functions at an absent
sibling-deck path. This isolated run instead received the machine-resolved
external closure under .flashcards/prerequisites/ and its authoritative
graph.json; the chapter edge and allowed capability summary match that staged
graph. No dependency edge was changed or inferred to bypass the isolation.

cold_start_status: pass
unresolved_dependencies: 0
