# Pilot cold-start audit: geometric language and measurement

cold_start_status: pass
unresolved_dependencies: 0

- Audit date: 2026-08-20
- Mode: novice-first build pilot
- Target: `flashcards/01_geometric_language_and_measurement.md`
- Write boundary checked: chapter 1 only; no later chapter card file was created,
  read, edited, or deleted.
- Scheduled inventory: 34 cards — 30 `Q/A`, 0 cloze, 4 `P/S`.
- Figure inventory: 9 original TikZ/SVG pairs plus one shared TikZ style.

## Frozen learner contract

The executable staged graph permits no local chapter knowledge inbound to
chapter 1. The only external knowledge admitted is the validator-resolved
closure supplied in `.flashcards/prerequisites/graph.json`:

- arithmetic, fractions, decimals, signed quantities, ratios, and percent;
- measurement, units, unit conversion, precision, rounded intervals, and
  quantitative reasonableness;
- variables, expressions, equations as equality statements, terms,
  coefficients, constants, substitution, evaluation, and verbal-expression
  translation.

No geometry vocabulary, drawing convention, geometry tool, coordinate plane,
equation-solving procedure, function graph, radical, or proof method is
inbound. The staged prerequisite chapter files contain bounded capability
summaries rather than card bodies, so no unstated knowledge was inferred from
the original decks. Assumed tools remain empty; ruler, protractor, compass, and
unmarked straightedge are taught as representations before use.

## Front-only cold-start scan

The scan was performed from an extraction containing only `Q:`, `C:`, and `P:`
fronts in source order. For each row, dependencies were recorded before its
`A:` or `S:` body was inspected. The back was then checked for later-facing
terms or methods.

| # | Stable card ID | Dependencies required by the front | Allowed source or earlier establishment | Back and first-use result | Status |
|---:|---|---|---|---|---|
| 1 | `f873cbb9-f8d6-4b33-8784-b48635055270` | dot, label, exact location, length/width | measurement inbound; point and dot grammar bridged on front | Back only grades the label's naming role | pass |
| 2 | `08af8a65-174f-4187-b66d-b5c14c11c09a` | straight drawing, continuation, arrowheads, line | point from 1; line and continuation grammar bridged on front and in alt text | No later object is named | pass |
| 3 | `d6312753-02aa-448e-8550-e404c88b5f81` | endpoint, segment, straightness | point from 1; endpoint and segment both bridged on front | Back identifies only the two visible endpoints | pass |
| 4 | `6f521b4a-9e34-40b3-b2b7-b18b0ca58ddd` | ray, endpoint, direction, arrowhead | endpoint from 3; ray and one-direction grammar bridged on front | Back retrieves start and direction | pass |
| 5 | `5ec34bd2-1212-4947-accf-2c7b959f6060` | three ending grammars, fixed start/end | line, segment, ray from 2–4; full figure repeated on this front | Back makes one segment-discrimination decision | pass |
| 6 | `9733d070-5d86-4161-a567-6c540b4a29ad` | line/segment symbol grammar | line and segment from 2–3; notation explained on front | Back translates both symbols as one contrast | pass |
| 7 | `bf934b35-8856-4172-828e-cd1617aaf47b` | ray notation and letter order | ray from 4; notation pattern from 6; endpoint-first rule bridged on front | Back explains the decisive endpoint change | pass |
| 8 | `2453c1b1-f2b5-4fd3-ad49-2e23e952773a` | plane, flat surface, bounded picture patch | point grammar from 1; plane and patch convention bridged on front | Back distinguishes picture boundary from mathematical object | pass |
| 9 | `563a0d35-ad24-435f-b8fa-2a29459427c1` | collinear, line notation | line from 2 and notation from 6; collinear defined on front | Back retrieves one term | pass |
| 10 | `08a5f200-5cd4-4b75-b4bf-c2b5c16b6f35` | intersection, shared point, two lines | point and line from 1–2; intersection defined on front | Back adds no new dependency | pass |
| 11 | `41b16040-1e51-46a7-a190-cdf48bb4cc87` | angle, sides, common endpoint, vertex | ray and endpoint from 3–4; all angle anatomy bridged on front | Back identifies the visible vertex | pass |
| 12 | `c41e695f-e00b-41cd-bd19-698c22913e2f` | three-letter angle naming | point labels from 1 and angle anatomy from 11; middle-letter rule on front | Back accepts both valid orders | pass |
| 13 | `a0262c87-a28b-4c0b-9f2c-8294ac138791` | angle object, numerical measure, equation | angle notation from 12; equations inbound; `m` distinction bridged on front | Back chooses measure notation only | pass |
| 14 | `a510405d-9b90-47a7-b78e-d9aa2c4a3ab5` | full turn, equal subdivision, degree symbol, fraction | number/fraction inbound; degree convention bridged on front | Back gives one fraction and identifies symbol | pass |
| 15 | `a0c5d131-9391-4fa3-ad9a-6f7adee70c29` | right and straight angle boundaries | angle and degree from 11–14; both classifications bridged on front | Back classifies one panel | pass |
| 16 | `8b84a176-1ec1-46e2-8fe5-c37a4863622b` | acute/obtuse intervals and comparison | angle/degree from 11–14; interval meanings bridged on front; figure repeated | Back classifies one panel | pass |
| 17 | `3d0e1f21-b396-496a-85a0-889d135985bb` | all four angle classes | right/straight from 15 and acute/obtuse from 16; figure repeated | Back retrieves straight-angle classification | pass |
| 18 | `d186d230-8226-4d6d-a689-0989dda4312e` | protractor, center mark, vertex, baseline | angle/vertex from 11; protractor and baseline defined on front | Back diagnoses one alignment error | pass |
| 19 | `afc0337c-2d1a-400a-a4df-82e115eef287` | two scales, zero origin, baseline | degree from 14 and protractor setup from 18; scale-choice rule on front | Back chooses the right-origin scale | pass |
| 20 | `aef59442-8f92-4091-86ec-2f31e68b4948` | centered protractor and scale reading | 18–19; visual values supplied accessibly | IPEE reads 60 degrees and rejects 120 by the right-angle bound | pass |
| 21 | `f4b892dc-1757-4bb9-9345-eeb10179aa1d` | segment, ruler readings, centimeters, subtraction | segment from 3; measurement/unit/subtraction inbound | IPEE computes 4.5 cm and checks by inverse addition | pass |
| 22 | `7d51f714-2ede-4766-801b-d1fbd6d6e662` | instrument precision versus stated value | measurement precision inbound; instruments from 18 and 21 | Back bounds the ruler reading's precision | pass |
| 23 | `eab7ca62-cb39-4c87-ad4e-c84ab73912b9` | convention, tick marks, equal length | segment from 3 and equality inbound; convention and marks bridged on front | Back states exactly the matching-mark group | pass |
| 24 | `2a045052-1a70-47cc-af19-075a90b3bf1a` | matching curved angle marks | angle from 11 and convention from 23; curved-mark meaning bridged on front | Back states equal angle measures without naming later arc concepts | pass |
| 25 | `fad577a0-470d-499e-8998-0e929fcc3120` | square-corner mark | vertex from 11, degree/right angle from 14–15, convention from 23 | Back states 90 degrees | pass |
| 26 | `c22f64a9-f924-49b9-a469-88ea4b793c44` | not-to-scale warning, labels, tick groups | precision from 22 and conventions from 23–25; figure is self-contained | Back follows the 6 cm label rather than appearance | pass |
| 27 | `cde5d830-4c17-4bea-ad28-605a9a858020` | ruler, numbered scale, unmarked straightedge | measurement inbound and line from 2; tool contrast bridged on front | Back selects alignment rather than measurement | pass |
| 28 | `fb08bade-9007-40e4-b048-3a84a92559bf` | compass, fixed opening, distance transfer | distance/measurement inbound and straightedge from 27; compass operation bridged on front | Back retrieves transfer rather than numerical reading | pass |
| 29 | `82d67767-541b-4e30-828b-19fb3fa6b5bd` | copy a segment on a ray; tool choice | segment/ray from 3–4 and tool roles from 27–28 | Back assigns one distinct job to each required tool | pass |
| 30 | `b252c6e4-19ca-4a77-a0ef-ddd030059a70` | construction, ideal relation, physical precision, fixed opening | precision from 22 and tools from 27–28; construction bounded on front | Back explains segment transfer without circle/arc vocabulary | pass |
| 31 | `2b7fe3bf-fab0-4343-9ebc-5d1624e230e2` | segment-copy construction and equality | 23 and 27–30; figure and alt text repeat all givens | IPEE concludes `CD=AB` and checks with the compass | pass |
| 32 | `a5165d61-b67d-4ee3-942f-95ea342d5c8a` | midpoint, point-on-segment, two equal lengths | point/segment from 1–3 and equality inbound; midpoint defined on front | Back states `AM=MB` | pass |
| 33 | `11e21657-9b77-44ef-b863-98bd0dfb5dc0` | compass marks, meetings, intersection, midpoint, ticks | intersection 10, tools 27–28, construction 30, midpoint 32, ticks 23 | Back states the intended midpoint equality; no symmetry/perpendicular term is imported | pass |
| 34 | `f01f837d-139d-457d-bc83-0ebe41848d44` | independent midpoint construction and check | every operation established by 10, 23, 27–33; half is inbound fraction knowledge | IPEE retains all stages and checks the two distances with one compass opening | pass |

Repairs made during the fronts-only scan:

1. Repeated the object figure on fronts 3–5 and the angle-class figure on
   fronts 16–17 so shuffled review never depends on a previous card.
2. Defined `endpoint` on front 3 rather than using it as hidden vocabulary.
3. Defined a protractor and its baseline on front 18 and removed the
   future-facing shape word `semicircular` from front 19.
4. Defined `diagram convention` on front 23.
5. Removed `symmetrically` from back 33 so chapter-3 symmetry vocabulary is not
   used to explain a chapter-1 result.

## Separate first-use scan

This pass searched fronts, image alt text, visible figure labels, and problem
setups independently of answer quality.

| First-use bundle | First supported front | Classification at first use | Later reuse checked | Result |
|---|---:|---|---|---|
| point, dot, capital label | 1 | self-bridged from inbound measurement words | all figures and naming | pass |
| line and two-arrow continuation | 2 | self-bridged with accessible visual grammar | 5–10, 33–34 | pass |
| endpoint and segment | 3 | both explicitly defined | 4–7, 21 onward | pass |
| ray and direction | 4 | explicitly defined from endpoint | 7, 11 onward | pass |
| line/segment/ray notation | 6–7 | symbol meaning explained before reuse | 9, 32–34 | pass |
| plane patch convention | 8 | explained and retrieved on same front | no unprepared later use | pass |
| collinear and intersection | 9–10 | separately defined and retrieved | construction diagrams | pass |
| angle, side, vertex | 11 | defined from established rays | 12–25 | pass |
| angle name and measure notation | 12–13 | middle-letter and `m` rules separately retrieved | angle measurement | pass |
| degree and degree symbol | 14 | self-bridged from full-turn fraction | 15–25 | pass |
| right/straight then acute/obtuse | 15–16 | linear micro-sequence before mixed front 17 | 18–26 | pass |
| protractor and baseline | 18 | tool and alignment defined | scale choice and problem 19–20 | pass |
| ruler endpoint-difference procedure | 21 | segment plus inbound subtraction; all readings supplied | precision front 22 | pass |
| measured versus stated precision | 22 | inbound precision applied to established tools | diagram evidence and construction boundaries | pass |
| tick, curved, and square-corner conventions | 23–25 | one convention per supported front | mixed not-to-scale front 26 and constructions | pass |
| ruler/straightedge contrast | 27 | explicit tool-role contrast | 29–34 | pass |
| compass fixed-distance transfer | 28 | operational definition | 29–34 | pass |
| construction | 30 | bounded as ideal relationship plus physical precision | 31, 33–34 | pass |
| midpoint | 32 | explicit point-on-segment and equality definition | 33–34 | pass |

No first-use front depends on parallel/perpendicular lines, transformations,
congruence, similarity, triangles, polygons, circles/arcs as named objects,
area, volume, coordinates, square roots, trigonometry, or formal proof. Curved
compass traces are described only as marks.

## Problem structure audit

All four `P:/S:` cards begin `S:` immediately with **IDENTIFY**, retain the
ordered **IDENTIFY → PLAN → EXECUTE → EVALUATE** sequence, and place the direct
result as the first sentence inside **EXECUTE**. Their checks are substantive:

- card 20 rejects the wrong protractor scale by the right-angle bound;
- card 21 reverses subtraction by addition and retains centimeters;
- card 31 rechecks both segments with one unchanged compass opening;
- card 34 compares the two candidate half-lengths with one compass opening.

No `A:` or `S:` body begins with a bare number and period.

## Figure audit

| Figure | Retrieval role | Frontier and accessibility check | Status |
|---|---|---|---|
| `object_endings` | distinguish endpoint and continuation grammars | Only points/letters and visible ending cues; repeated where referenced | pass |
| `plane_patch` | translate bounded drawing to unbounded plane | Caption explains picture boundary on first-use front | pass |
| `angle_anatomy` | locate vertex and sides spatially | Uses only established points/rays; alt does not name the answer | pass |
| `angle_classes` | translate degree values to four classes | Appears only after degree bridge; repeated for shuffled review | pass |
| `protractor_measure` | choose dual scale and read angle | Appears after protractor/baseline bridge; both scale values accessible | pass |
| `offset_ruler` | subtract offset endpoint readings | Centimeters and subtraction are inbound; endpoints/readings accessible | pass |
| `diagram_evidence` | prefer explicit labels/mark groups over appearance | One-tick and two-tick groups are consistent with unequal stated values | pass |
| `copy_segment_steps` | inspect unchanged compass transfer | Appears after compass/straightedge roles; avoids circle/arc terminology | pass |
| `midpoint_construction` | translate equal-distance marks to midpoint | Appears after intersection, ticks, compass, construction, and midpoint | pass |

All figures use compact coordinates near the origin, tight centered canvases,
high-contrast strokes plus non-color cues, responsive SVG `viewBox` attributes,
meaningful embedded `<title>`/`<desc>`, and meaningful Markdown alt text. Each
TikZ source loads `figures/tikz-style.tex`; sources and SVG outputs are paired.
Phone-width visual inspection found and repaired one contradictory tick pattern
in `diagram_evidence` and one overflowing heading in `copy_segment_steps`.

## Planned-versus-actual reconciliation

| Inventory | Planned | Actual | Reconciliation |
|---|---:|---:|---|
| `Q/A` | 30 | 30 | exact match |
| Cloze | 0 | 0 | notation requires interpretation and discrimination, not isolated exact deletion |
| `P/S` | 4 | 4 | exact match |
| Figures | 9 | 9 | every planned distinct retrieval role included |

The problem arc is two independent instrument readings, a segment-copy
construction justification, and an independent midpoint construction. The
planned construction-completion slot became a construction-justification
problem because the authentic step figure necessarily displays the placed
mark; asking for the visible next step would leak the answer. The revised
problem instead retrieves the invariant fixed opening and remains a genuine
method decision.

Intentional omissions remain: decorative photographs, tool-recognition icons,
image-based notation tables, angle copying/bisection, parallel/perpendicular
construction terminology, coordinate grids, transformations, named circles or
arcs, polygons, and proof syntax. These omissions preserve the chapter-1
concept frontier and do not remove any declared chapter capability.

## Conclusion

Every scheduled front maps to confirmed inbound knowledge, an earlier
establishment, or a minimal same-front bridge using only established language.
Every back was checked for terminology later fronts reuse. No blocked or
unresolved dependency remains. The pilot is ready for human review; later
chapters remain unauthored.
