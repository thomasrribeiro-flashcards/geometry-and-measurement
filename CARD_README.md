# Geometry And Measurement card blueprint

This file records retrieval decisions specific to this deck. Do not copy the
universal standard, playbook, subject brief, roadmap, or research literature
here; link to a justified exception when one is necessary.

## Learner model

- Level: foundational; motivated adult self-learner working independently.
- Confirmed mathematical/tool prerequisites: no tools. The resolved transitive
  closure confirms arithmetic, fractions, decimals, ratio/proportion, signed
  coordinates, percent, measurement, units, conversion, precision, and
  reasonableness.
- Confirmed direct-deck capabilities: variable and expression language,
  equations as equality statements, terms, coefficients, constants,
  substitution, expression evaluation, and verbal-expression translation.
- Capabilities this deck should produce: diagram literacy, geometric
  construction and measurement, angle and triangle reasoning, transformations,
  congruence, similarity, circle and right-triangle reasoning, coordinate
  arguments, plane and solid measurement, and bounded modeling with honest
  units and precision.
- Important exclusions: no general equation-solving or function-graphing is
  assumed; no conics, circular functions, advanced trigonometric laws, vectors,
  projective/non-Euclidean geometry, formal axiomatic systems, or long proof
  writing. These are handed to later mathematics decks or external practice.

Unconfirmed subject knowledge is not mastered. A target level describes the
destination, not permission to assume its vocabulary.

## Curriculum and prerequisite graph

The plan follows a transformation-first progression: precise objects and
measurement support angle reasoning and rigid motions; those jointly support
triangle congruence; congruence and dilation support similarity; similarity
then supports scale, measurement, and right-triangle trigonometry. Coordinate
proof waits for the Pythagorean theorem, while solid measurement branches from
plane/circle measurement and right triangles rather than depending on file
order.

Rejected hard edges:

- chapter 3 does not depend on chapter 2; basic transformations need measured
  objects and angles, not transversal theorems;
- chapter 8 does not depend on chapter 7; right-triangle ratios arise from
  similarity, not circles;
- chapter 10 does not depend on chapter 9; coordinates are not required for
  nets, cross-sections, surface area, or volume.

Machine-readable edges remain solely in chapter frontmatter. Inspect them with
`flashcards deck prerequisites .`.

## Concept-dependency ledger

This plan records the frontier by concept bundle. During pilot or chapter
authoring, split each row into individual terms, symbols, figure grammars, and
procedures and replace the planned locations with actual stable card IDs.

| New concept bundle | Allowed inbound source | Planned first explanation and supported retrieval | Later application | Status |
|---|---|---|---|---|
| Point, line, plane, ray, segment, distance, angle, degree, congruence marks, construction marks | Resolved arithmetic/measurement closure | Ch. 1 diagram-reading and tool-use micro-sequences | Every later chapter | planned |
| Angle pairs, perpendicular/parallel lines, transversal relationships, reason/conclusion language | Ch. 1 | Ch. 2 relationship diagrams followed by one-step justifications | Chs. 4, 7, 9 | detailed below |
| Translation, reflection, rotation, invariant, symmetry, composition | Ch. 1 plus signed coordinates inbound | Ch. 3 physical/coordinate before-and-after transformations | Chs. 4, 5, 9 | planned |
| Triangle classes, corresponding parts, congruence, SSS/SAS/ASA/AAS/HL, insufficient data | Chs. 2–3 | Ch. 4 rigid-motion bridge, supported criterion choice, then deductions | Chs. 5, 6, 9 | planned |
| Dilation, center/scale factor, similarity, AA, corresponding proportion, scale drawing | Ch. 4 plus inbound ratio/proportion | Ch. 5 dilation sequences and matched-side tables | Chs. 6, 8, 10 | planned |
| Perimeter, base/height, area, decomposition, composite region, square unit, area scale | Ch. 5 plus inbound units | Ch. 6 tiling/dissection explanations before formula choice | Chs. 7, 9, 10 | planned |
| Radius, diameter, chord, arc, sector, tangent, circumference, pi, central/inscribed angle | Ch. 6 | Ch. 7 circle anatomy and proportional-measure sequences | Ch. 10 | planned |
| Hypotenuse/leg, square root as a length, Pythagorean relation, sine/cosine/tangent for acute angles | Ch. 5 plus inbound powers/proportions | Ch. 8 similarity and area bridges before ratio selection | Chs. 9–10 | planned |
| Ordered pair geometry, midpoint, distance, slope criteria, coordinate proof | Chs. 4 and 8 plus inbound signed arithmetic | Ch. 9 geometric meaning before formulas and theorem checks | Later algebra/precalculus | planned |
| Net, cross-section, prism, pyramid, cylinder, cone, sphere, surface area, volume, cubic scale, geometric model | Chs. 7–8 | Ch. 10 unfolding/slicing and unit-cube explanations before formula choice | Later modeling/calculus | planned |

Rejected examples must be logged during authoring whenever they require
unavailable equation-solving, circular functions, vectors, conics, or later
proof machinery. Seeing an answer after an uninformed failure never counts as
the first explanation.

## Retrieval portfolio

The portfolio emphasizes classification, representation translation, theorem or
method choice, error diagnosis, and short execution. Exact compact notation or
hypotheses may become clozes only after meaning has been established. Problems
progress from analyzed diagrams to completion, faded, independent, and mixed
decisions; extended proofs and designs stay outside SRS.

High-priority interference pairs are line/segment/ray; drawing/claim;
adjacent/vertical and complementary/supplementary; rigid/non-rigid motion;
congruent/similar; SSS/SAS/SSA; length/area/volume scale; radius/diameter and
arc/sector; sine/cosine/tangent; distance/slope; surface area/volume; exact
geometric value/measured approximation. Contrast cards follow separate
establishment of both neighbors.

## Chapter design ledger

Complete this before large-scale authoring and reconcile it at handoff. Add rows
or split columns when a chapter has several distinct figures or problems.

| Chapter | Purpose and retrieval targets | Planned card roles | Planned problem progression | Representations, figure opportunities, and boundary |
|---|---|---|---|---|
| 1. Geometric language and measurement | Establish objects, notation, diagram conventions, segment/angle measure, precision, and straightedge/compass/ruler/protractor roles. Retrieve distinctions such as line vs. segment vs. ray and measured evidence vs. a stated claim. | `Q/A` for diagram reading, notation translation, tool choice, and misconception diagnosis. Cloze only for compact, already-understood notation conventions. | Analyzed reading → complete a construction step → independently measure/draw to stated precision → mixed tool/notation choice. | **Plan:** object/notation diagrams; protractor and ruler scales; compass-circle and perpendicular-bisector constructions; deliberately not-to-scale counterexample. **Omit:** decorative photographs. Handoff formal construction proofs to later proof study. |
| 2. Angle relationships and parallel lines | Use adjacent, vertical, complementary, supplementary, linear-pair, perpendicular, and transversal relationships; state a short chain of reasons. | `Q/A` for relationship recognition, prediction, and invalid-reason diagnosis; possible cloze for a compact established angle relation. | Analyzed marked diagram → one missing angle with named reason → faded multi-relation chain → mixed parallel/nonparallel discrimination. | **Plan:** vertical/linear-pair overlay; parallel-lines/transversal families with redundant markings; short reason-conclusion flow. **Omit:** figures whose labels reveal the target angle. Handoff formal proof syntax to `mathematical-reasoning-and-proof`. |
| 3. Transformations and symmetry | Perform translations, reflections, and rotations; identify preserved distance/angle/orientation; compose motions; locate line and rotational symmetry. | `Q/A` for transformation classification, invariant prediction, coordinate/diagram translation, and order-of-composition diagnosis. Cloze only for compact invariant vocabulary after retrieval. | Analyzed before/after motion → complete an image point → faded whole-figure transformation → independent composition and symmetry discrimination. | **Plan:** tracing-paper style overlays; coordinate before/after grids; reflection line and rotation-center constructions; symmetry-axis and rotational-order figures. **Omit:** software screenshots because no tool is assumed. Stretch/shear appear only as non-rigid contrasts. |
| 4. Triangle congruence and reasoning | Classify triangles; connect rigid motion to congruence; select SSS, SAS, ASA, AAS, or HL; reject SSA/AAA as congruence data; derive triangle-sum, exterior-angle, and isosceles facts. | `Q/A` for criterion choice, correspondence, counterexample, and reason diagnosis; exact criterion names may become clozes after meaning. | Analyzed matching → criterion completion → faded missing-measure deduction → independent mixed sufficient/insufficient-data and short proof spine. | **Plan:** correspondence markings; rigid-motion superposition; hinge/ambiguous SSA counterexample; auxiliary-line construction for a triangle result. **Omit:** memorized paragraph proofs. Handoff general proof methods later. |
| 5. Similarity, dilations, and scale | Distinguish similarity from congruence; use center and scale factor; establish AA; match corresponding sides; solve proportional scale and indirect-measurement problems. | `Q/A` for dilation effects, correspondence, method selection, and congruent/similar contrast; cloze only for a compact scale relation after visual grounding. | Analyzed dilation → complete a corresponding-side table → faded similar-triangle proportion → independent scale drawing/indirect measure with plausibility check. | **Plan:** center-of-dilation ray diagram; same-shape different-size overlays; similar-triangle correspondence; scale map/plan. **Omit:** distorted perspective drawings. Handoff circular trig and vectors to precalculus. |
| 6. Plane measurement and area | Choose and justify perimeter/area formulas for triangles, quadrilaterals, regular polygons, and composite regions; use decomposition, missing-area subtraction, units, and linear-vs-area scale. | `Q/A` for formula choice, base-height identification, dissection reasoning, unit/error diagnosis; compact established formulas are possible clozes, never their derivations. | Tiled/analyzed region → complete a decomposition → faded composite-area calculation → independent design/scale comparison with unit and bound checks. | **Plan:** unit tiling; parallelogram/triangle rearrangements; trapezoid decomposition; composite and shaded regions; scale-factor tile comparison. **Omit:** answer-revealing dimensions on fronts. Circle area waits for ch. 7. |
| 7. Circles, arcs, and sectors | Relate radius, diameter, circumference, area, chords, central/inscribed angles, arcs, sectors, and tangent-radius geometry; use proportional measures and approximations honestly. | `Q/A` for anatomy, relationship selection, exact-vs-approximate answer, and tangent/angle diagnosis; compact formulas may be clozed only after derivation. | Analyzed circle anatomy → complete circumference/area relation → faded arc/sector proportion → independent mixed circle measure/tangent problem. | **Plan:** radius/diameter/chord/tangent anatomy; circumference unwrapping or polygon approximation; central/inscribed angle pair; arc-sector proportion. **Omit:** unexplained limit arguments and external circle art. Full conic equations wait for algebra/precalculus. |
| 8. Right triangles and trigonometry | Establish square root as a nonnegative length, prove/use the Pythagorean theorem, recognize converses, derive acute-angle sine/cosine/tangent from similarity, and choose a ratio to solve right triangles. | `Q/A` for side-role identification, theorem/ratio selection, qualitative prediction, exact/approximate form, and calculator-free table interpretation. Cloze only for established ratio definitions. | Analyzed similarity/Pythagorean model → complete one side/ratio → faded triangle solution → independent height/distance problem and mixed theorem-vs-trig choice. | **Plan:** Pythagorean dissection or similar-triangle proof figure; nested similar right triangles; opposite/adjacent/hypotenuse diagrams keyed to a marked angle; inaccessible-height model. **Omit:** unit-circle graphs and laws of sines/cosines. Numerical trig values must be supplied if a calculator would otherwise be required. |
| 9. Coordinate geometry and geometric proof | Connect geometric objects to ordered pairs; compute midpoint and distance; perform coordinate transformations; use slope to test parallel/perpendicular lines and coordinates to justify elementary figure properties. | `Q/A` for formula meaning, invariant translation, slope/distance method choice, and proof-step diagnosis; cloze only for established compact coordinate relations. | Analyzed coordinate segment → complete distance/midpoint or image point → faded slope criterion → independent polygon classification/short coordinate proof with arithmetic checks. | **Plan:** coordinate grids for distance, midpoint, and transformations; rise/run triangles; parallel/perpendicular comparisons; polygon proof setup. **Omit:** full line/circle equations, completing the square, conics, and vector/matrix notation until later decks. |
| 10. Surface area, volume, and modeling | Interpret nets, cross-sections, and solids of rotation; derive/select surface-area and volume formulas; distinguish square/cubic scale; estimate, model, and critique assumptions. | `Q/A` for net/solid translation, formula choice, cross-section prediction, scale reasoning, unit/model diagnosis; established formulas may later support compact clozes. | Analyzed unit cubes/net → completion of a composite surface/volume → faded prism/cylinder/pyramid/cone/sphere problem → independent model comparison with precision and sensitivity check. | **Plan:** nets and fold pairs; cross-sections; unit-cube arrays; prism/cylinder and pyramid/cone comparisons; Cavalieri-style equal-height slices; object-to-ideal-solid model. **Omit:** decorative 3-D renderings and calculus derivations. Fabrication/design remains external practice. |

Card-form diversity is not a goal by itself. Zero clozes can be correct. A
visually rich chapter may require several figures because diagrams, graphs,
before/after states, and spatial constructions serve different retrieval roles.

### Pilot chapter 1 detailed design ledger

This ledger freezes the chapter-1 design before card authoring. The resolved
inbound frontier is limited to the validator-declared arithmetic, measurement,
unit, precision, reasonableness, variable, expression, equation, substitution,
and verbal-expression capabilities. No geometry term or drawing convention is
inbound.

| Retrieval sequence | Target and card form | Supported-to-independent progression | Authentic representation or figure decision |
|---|---|---|---|
| 1–5 | Interpret a point as an ideal location; distinguish line, segment, and ray from endpoints and continuation marks (`Q/A`). | Minimal bridge on each front → identify one object from the visual grammar → mixed three-object discrimination. | **Include `object_endings`:** the presence of endpoints and one/two continuation arrows is itself the retrieval evidence. |
| 6–10 | Translate line/segment/ray notation; use ray letter order; interpret a plane patch; recognize collinear points and an intersection (`Q/A`). | Explained notation → one-symbol translation → direction contrast → spatial reading needed by construction diagrams. | **Include `plane_patch`:** a bounded slanted patch must be read as a conventional picture of an unbounded flat surface. **Omit a separate notation table figure:** KaTeX is clearer and accessible. |
| 11–17 | Interpret an angle as two rays with a common endpoint; locate its vertex and sides; name it with the vertex letter in the middle; distinguish angle from angle measure; use degrees; classify measured angles (`Q/A`). | Anatomy bridge → supported naming → notation contrast → exact boundary and interval classifications. | **Include `angle_anatomy` and `angle_classes`:** vertex position and amount of turn are spatial targets. Defer adjacent, vertical, complementary, supplementary, and parallel-line relationships to chapter 2. |
| 18–21 | Align a protractor, select the scale beginning at the chosen zero, and read a degree measure; compute a segment length from two ruler readings (`Q/A`, then two `P/S`). | Analyzed alignment → independent protractor read → independent endpoint subtraction on an offset ruler. | **Include `protractor_measure` and `offset_ruler`:** both are authentic instrument-scale translations. **Omit photographs:** they add visual noise and introduce licensing overhead without improving the decision. |
| 22–26 | Distinguish measured approximation from exact stated information; interpret equal-length ticks, equal-angle arcs, and a square-corner mark; let stated marks and values override apparent scale (`Q/A`). | Explain each mark separately → retrieve its claim → diagnose a deliberately misleading sketch. | **Include `diagram_evidence`:** conflicting visual size and explicit marks make the drawing-versus-claim distinction retrievable. |
| 27–29 | Choose among ruler, unmarked straightedge, compass, and protractor; explain that a compass transfers a fixed distance without reporting a number (`Q/A`). | Tool-role explanations → mixed tool choice. | **Omit tool icons:** the target is the operation each tool supports, not object recognition. |
| 30–31 | Read and complete a segment-copy construction (`Q/A`, then `P/S`). | Analyzed compass transfer → completion problem that chooses and executes the next construction step. | **Include `copy_segment_steps`:** the unchanged compass opening and target ray must be inspected. |
| 32–34 | Define a midpoint and interpret/complete a compass-and-straightedge midpoint construction (`Q/A`, `Q/A`, then `P/S`). | Definition → analyzed equal-distance marks → independent construction plan and check. | **Include `midpoint_construction`:** crossing equal-distance marks explain why the constructed point is halfway. Do not name the resulting line as perpendicular; that term belongs to chapter 2. |

Planned inventory: **30 `Q/A`, 0 cloze, 4 `P/S`, 9 figures**. The four
problems progress from instrument reading (ruler and protractor), through a
construction completion, to an independent midpoint construction. Every
problem retains the complete ordered IDENTIFY → PLAN → EXECUTE → EVALUATE
sequence. Exact drawing and longer construction practice remain outside SRS.

Plausible opportunities intentionally omitted: decorative photographs; a
symbol table rendered as an image; pictures of tools; parallel-line and
perpendicular-line constructions, whose vocabulary is established in chapter
2; copied-angle and bisected-angle procedures, which would lengthen this pilot
without adding a new tool grammar; coordinate grids, transformations, circles,
polygons, and formal proofs, all of which lie beyond the chapter frontier.

### Pilot chapter 1 concept-dependency ledger (pre-authoring)

`P01`–`P34` are frozen drafting positions, not card identities. They will be
replaced by stable `card-id` values after the fronts are authored. A bridge and
retrieval may share a front only when the bridge uses inbound or already
established language and makes one bounded successful inference possible.

Allowed inbound knowledge is limited to: number and arithmetic operations;
subtraction and inverse-operation checks; fractions and decimals; measurement,
units, conversion, precision, rounded intervals, and reasonableness; variables,
expressions, equations as equality statements, substitution, evaluation, and
translation between verbal and symbolic expressions. No geometry vocabulary,
tool grammar, or diagram mark is inbound.

| New concept, symbol, or representation | First explanation | First supported retrieval | Later application | Pre-authoring status |
|---|---|---|---|---|
| Point; dot and capital-letter convention | P01 bridge | P01 | P02 onward | ready |
| Line; straightness; continuation in two directions; two arrowheads | P02 bridge | P02 | P05–P10 | ready |
| Segment; two endpoints | P03 bridge | P03 | P05–P10, P19, P22, P30–P34 | ready |
| Ray; endpoint and one direction; one arrowhead | P04 bridge | P04 | P05–P17, P31 | ready |
| Mixed line/segment/ray diagram grammar | P02–P04 | P05 | P06–P07 | ready |
| Segment notation `\overline{AB}` and line notation `\overleftrightarrow{AB}` | P06 bridge | P06 | P19, P22, P30–P34 | ready |
| Ray notation `\overrightarrow{AB}` and order-dependent direction | P06 bridge | P07 | P11 onward | ready |
| Plane; bounded patch as an unbounded flat-surface convention | P08 bridge | P08 | later spatial diagrams | ready |
| Collinear | P09 bridge | P09 | P10, P30–P34 | ready |
| Intersection as a shared point | P10 bridge | P10 | P30–P34 | ready |
| Angle; two rays; common endpoint; sides; vertex | P11 bridge | P11 | P12–P18, P20, P24–P25 | ready |
| Three-letter angle notation with vertex in the middle | P12 bridge | P12 | P13 onward | ready |
| Angle object `\angle ABC` versus measure `m\angle ABC` | P13 bridge | P13 | P14–P25 | ready |
| Degree and degree symbol; one degree as 1/360 of a full turn | P14 bridge | P14 | P15–P20 | ready |
| Right and straight angle classifications | P15 bridge | P15 | P17–P18, P25 | ready |
| Acute and obtuse angle classifications | P16 bridge | P16 | P17–P18 | ready |
| Angle-class visual translation | P15–P16 | P17 | later angle reasoning | ready |
| Protractor; center, baseline, zero choice, dual scale | P18 bridge | P18 | P20, P29 | ready |
| Reading angle measure from a protractor | P18 | P20 problem | later angle measurement | ready |
| Segment length as difference of endpoint ruler readings | inbound subtraction plus P19 setup | P19 problem | P22, P30–P34 | ready |
| Measured approximation versus exact stated value | inbound precision plus P22 bridge | P22 | P26, problem checks | ready |
| Matching segment tick marks state equal lengths | P23 bridge | P23 | P26, P30–P34 | ready |
| Matching angle arcs state equal angle measures | P24 bridge | P24 | P26 and chapter 2 | ready |
| Square-corner mark states a 90-degree angle | P25 bridge | P25 | P26 and chapter 2 | ready |
| Not-to-scale diagram; explicit labels and marks override appearance | P26 bridge | P26 | every later chapter | ready |
| Ruler versus unmarked straightedge | P27 bridge | P27 | P29–P34 | ready |
| Compass as fixed-distance transfer tool | P28 bridge | P28 | P30–P34 | ready |
| Tool-choice discrimination among ruler, straightedge, compass, protractor | P27–P28 and P18 | P29 | P30–P34 | ready |
| Construction as steps producing an exact relationship rather than a measured estimate | P30 bridge | P30 | P31–P34 | ready |
| Copying a segment with unchanged compass opening | P30 analyzed example | P31 problem | later constructions | ready |
| Midpoint as a point on a segment with two equal subsegment lengths | P32 bridge | P32 | P33–P34 | ready |
| Equal-distance compass marks from both endpoints | P33 analyzed example | P33 | P34 | ready |
| Compass-and-straightedge midpoint construction | P33 analyzed example | P34 problem | later bisector constructions | ready |

Future-facing examples rejected before drafting: slopes and coordinate grids;
parallel or perpendicular terminology; transformations and congruence;
triangles, polygons, and circles as named objects; area and volume; square
roots and trigonometric ratios; formal proof vocabulary. A curved compass mark
will be described operationally rather than named with chapter-7 circle or arc
terminology.

### Chapter 2 detailed design ledger

This ledger freezes the chapter-2 design before card authoring. The allowed
frontier is the resolved arithmetic/algebra capability summary plus all 34
scheduled cards in chapter 1. In particular, the learner knows line, ray,
segment, angle, vertex, angle measure in degrees, right and straight angles,
angle/segment diagram marks, exact-versus-measured evidence, and construction
language. General equation solving, equality properties, slope, coordinates,
transformations, triangles, congruence terminology, and formal proof syntax are
not inbound.

| Retrieval sequence | Target and card form | Supported-to-independent progression | Authentic representation or figure decision |
|---|---|---|---|
| P01–P08 | Recognize adjacent, complementary, supplementary, opposite-ray, linear-pair, and vertical-angle relationships; explain why vertical angles have equal measures (`Q/A`). | Self-bridged relationship → supported identification → adjacent-versus-complementary discrimination → linear-pair inference → analyzed vertical-angle reason. | **Include `angle_pair_families` and `intersecting_lines`:** shared sides, opposite rays, and opposite angle regions are spatial evidence. **Omit a term table:** prose and KaTeX are more accessible and do not test a visual decision. |
| P09 | Determine an unknown measure at one intersection and justify it (`P/S`). | Completion problem using one linear-pair relation and a genuine straight-angle check. | Reuse **`intersecting_lines`** with a stated measure; no answer labels appear in the asset. |
| P10–P15 | Interpret perpendicular and parallel definitions, symbols, lowercase line labels, and body marks; distinguish stated marks from appearance (`Q/A`). | Definition and notation bridge → consequence of one right angle → definition and marking bridge → marked/unmarked discrimination. | **Include `line_relationships`:** perpendicular square marks, parallel body marks, and visually similar unmarked lines must be read. **Omit construction cards:** exact perpendicular/parallel construction needs sustained drawing practice and adds no new relationship decision here. |
| P16–P24 | Interpret a transversal, numbered angle regions, interior/exterior position, and corresponding, alternate-interior, alternate-exterior, and same-side-interior pairs; apply the parallel-line angle results (`Q/A`). | Diagram-grammar bridge → region retrieval → one family at a time → theorem use with the parallel condition stated → condition diagnosis. | **Include `transversal_families`:** two intersections and marked angle regions are the authentic representation. Reuse one stable numbering only for initial learning; the problems vary the givens and requested relations. |
| P25–P27 | Find a corresponding measure, complete a two-reason angle chain, and reject a parallel-line inference when no parallel evidence is present (`P/S`, `P/S`, `Q/A`). | One-step completion → faded two-step chain → misconception diagnosis. | Reuse **`transversal_families`** and include **`unmarked_transversal`** for the missing-hypothesis contrast. |
| P28–P30 | Use a valid angle relationship in reverse to establish parallel lines; give a short reason-conclusion chain, including the case of two lines perpendicular to one line (`P/S`, `Q/A`, `P/S`). | Supported converse decision → name the required evidence → independent mixed argument. | **Include `perpendiculars_to_transversal`:** two square marks provide non-color evidence for the final short argument. **Omit formal two-column proof flow:** general proof syntax belongs to the later proof deck; the complete reason chain remains in prose. |

Planned inventory: **25 `Q/A`, 0 cloze, 5 `P/S`, 6 figures**. The five
problems progress from an intersecting-line completion, through one-step and
two-step parallel-transversal calculations, to a converse classification and
an independent short geometric argument. Every problem retains the complete
ordered IDENTIFY → PLAN → EXECUTE → EVALUATE sequence. No cloze is planned
because the new vocabulary first needs spatial discrimination and bounded
reasoning rather than context-light exact insertion.

Plausible opportunities intentionally omitted: photographs of roads or rails,
which are decorative and may falsely suggest that appearance proves
parallelism; protractor remeasurement, already established in chapter 1;
perpendicular and parallel construction sequences, better practiced by drawing;
coordinate grids and slope criteria, reserved for chapter 9; triangle examples,
reserved for chapter 4; transformation explanations, reserved for chapter 3;
and formal proof layouts, reserved for `mathematical-reasoning-and-proof`.

### Chapter 2 concept-dependency ledger (pre-authoring)

`P01`–`P30` are frozen drafting positions, not card identities. A bridge and
retrieval share a front only when the bridge uses inbound or earlier-established
language and supports one bounded decision.

| New concept, symbol, or representation | First explanation | First supported retrieval | Later application | Pre-authoring status |
|---|---|---|---|---|
| Adjacent angles; shared vertex and side; nonoverlapping angle regions | P01 bridge and figure | P01 | P04–P09 | ready |
| Complementary angles; measures total \(90^\circ\); adjacency not required | P02 bridge | P02 | P04, P11 | ready |
| Supplementary angles; measures total \(180^\circ\); adjacency not required | P03 bridge | P03 | P04–P09, P24–P27 | ready |
| Relationship-versus-position discrimination | P01–P03 | P04 | P05 onward | ready |
| Opposite rays as rays sharing an endpoint and continuing in opposite directions on one line | P05 bridge | P05 | P06–P09 | ready |
| Linear pair as adjacent angles with opposite nonshared sides | P05 | P06 | P07–P09, P24–P27 | ready |
| Vertical angles as opposite angle regions made by intersecting lines | P07 bridge and figure | P07 | P08–P09, P24–P27 | ready |
| Vertical-angle equality and its shared-straight-angle reason | P08 analyzed argument | P08 | P09, P24–P27 | ready |
| Perpendicular lines and \(\perp\) | P10 bridge | P10 | P11, P29–P30 | ready |
| One right-angle intersection forces four right angles | P11 bridge using P07–P08 and supplementary angles | P11 | P30 | ready |
| Lowercase line labels | P10 bridge | P10 | P12 onward | ready |
| Parallel lines in one plane; \(\parallel\) | P12 bridge | P12 | P13–P30 | ready |
| Matching parallel body marks versus continuation arrowheads | P12 bridge and figure | P12 | P13–P30 | ready |
| Appearance is not parallel-line evidence | inbound diagram-evidence convention plus P13 | P14 | P27 | ready |
| Parallel-versus-perpendicular discrimination | P10–P14 | P15 | P16 onward | ready |
| Transversal as a line intersecting two lines at different points | P16 bridge and figure | P16 | P17–P30 | ready |
| Numeral inside an angle region as its short name | P01 bridge | P01 | P06–P28 | ready |
| Interior and exterior regions for two lines cut by a transversal | P17 bridge | P17 | P18–P28 | ready |
| Corresponding angles as matching corners at the two intersections | P18 bridge | P18 | P22, P25, P28–P30 | ready |
| Alternate interior angles | P19 bridge | P19 | P22–P28 | ready |
| Alternate exterior angles | P20 bridge | P20 | P22–P28 | ready |
| Same-side interior angles | P21 bridge | P21 | P23–P28 | ready |
| Parallel-transversal equal-measure results for corresponding and alternate pairs | P22 bridge with explicit parallel condition | P22 | P24–P26 | ready |
| Parallel-transversal supplementary result for same-side interior pairs | P23 bridge with explicit parallel condition | P23 | P24–P27 | ready |
| Parallel evidence as a required hypothesis | P12–P14 plus P22–P23 | P24 | P25–P27 | ready |
| Short reason-conclusion chain | P08 analyzed reason and P25–P26 worked problems, then P29 explicit bridge | P29 | P30 | ready |
| Reverse angle test for parallel lines | P28 problem bridge using corresponding-angle equality | P28 | P29–P30 | ready |
| Two lines perpendicular to one line are parallel, via equal corresponding right angles | P29 bridge | P29 | P30 | ready |

First-use exclusions: the chapter will not use *congruent* for equal angle
measure, *slope*, coordinate notation, transformation language, triangle or
polygon names, circle/arc/sector terminology, or formal proof vocabulary.
Every transversal result states or visibly marks the parallel hypothesis; an
unmarked look-alike is reserved for diagnosing the missing premise.

### Chapter 2 inventory reconciliation

The authored inventory matches the frozen design: **25 Q/A, 0 cloze,
5 P/S, and 6 TikZ/SVG figures**. The problems progress from one-intersection
completion to one-step and two-step transversal calculations, then a reverse
parallel test and an independent perpendicular-to-parallel argument. The six
figures retain distinct retrieval roles: angle-pair arrangement, one
intersection, line relationship marks, transversal families, a missing-mark
contrast, and two perpendicular relationships to one transversal. No planned
card form, problem stage, or figure role was omitted.

The intentionally omitted opportunities remain decorative road/rail
photographs, repeated instrument measurement, exact construction sequences,
coordinate/slope representations, triangle or transformation examples, and
formal proof layouts. The completed front-by-front dependency and first-use
scan is recorded in
.flashcards/audits/02_angle_relationships_and_parallel_lines-cold-start.md.

## Initial-learning path

Every new bundle begins with a scheduled, diagram-supported orientation using
only resolved inbound language; the next scheduled card asks one supported
retrieval decision, followed by a representation change, contrast, and then a
short application. A formula is first connected to a construction,
decomposition, invariant, similarity argument, or unit model before exact recall
or independent use. Tool grammars (protractor scales, congruence ticks,
transformation arrows, coordinate grids, nets, cross-sections) are explained on
a scheduled front before a card asks the learner to interpret them.

Chapter 1 is the approved pilot recorded in deck.toml. Before each later
chapter, replace its bundle-level plan with card-level dependencies and run a
chapter-boundary front-only cold-start simulation. A failed card must expose a
retrieval or reasoning gap, not missing instruction.

## Figure policy

Add a figure only when inspecting, predicting, labeling, comparing, tracing, or
translating it is part of learning. Author new technical figures in TikZ by
default, compile them to responsive SVG before handoff, and commit source and
output together under repository-root `figures/NN_chapter/`; keep the shared
style at `figures/tikz-style.tex` and never create `flashcards/figures/`. Since
rendering runs from the repository root, load it with
`\\input{figures/tikz-style.tex}` rather than a source-relative path. Put
setup figures on the front and answer-revealing
annotations on the back. Record why an authentic target requires another medium.

Do not treat one figure per chapter as a target or cap. Inventory every
plausible spatial, temporal, structural, graphical, relational, experimental,
and before/after representation, then include or explicitly omit it according
to its retrieval value.

## Sources and accuracy

The researched curriculum and convention sources are registered in `README.md`.
Later authoring must add claim-verification sources as needed and must label
diagram-not-to-scale assumptions, exact versus measured/rounded quantities,
orientation and correspondence conventions, degree/radian choices, calculator
or supplied-table assumptions, and any quoted-without-proof result. No
substantive mathematical controversy is identified at this level; differing
notation and construction conventions must be named when they affect grading.

## Validation gate

For a chapter-sized build handoff:

1. Run flashcards deck stabilize . --check.
2. Run flashcards deck prerequisites . --chapter <number> and reconcile the
   result with the staged machine-resolved closure in an isolated run.
3. Run flashcards deck validate . and require zero parser, KaTeX, image,
   identity, markup, cloze, and frontmatter findings.
4. Run flashcards deck render-figures . --check, inspect every changed figure,
   and confirm accessible titles/descriptions and tight centered canvases.
5. Run git diff --check and review the complete diff for accidental content,
   identity, prerequisite, or scope changes.
