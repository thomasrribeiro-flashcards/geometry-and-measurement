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
| Angle pairs, perpendicular/parallel lines, transversal relationships, reason/conclusion language | Ch. 1 | Ch. 2 relationship diagrams followed by one-step justifications | Chs. 4, 7, 9 | planned |
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

## Initial-learning path

Every new bundle begins with a scheduled, diagram-supported orientation using
only resolved inbound language; the next scheduled card asks one supported
retrieval decision, followed by a representation change, contrast, and then a
short application. A formula is first connected to a construction,
decomposition, invariant, similarity argument, or unit model before exact recall
or independent use. Tool grammars (protractor scales, congruence ticks,
transformation arrows, coordinate grids, nets, cross-sections) are explained on
a scheduled front before a card asks the learner to interpret them.

Only chapter 1 may be authored as the pilot. Before any later chapter, replace
the bundle-level ledger with card-level dependencies, run the front-by-front
cold-start simulation, save `.flashcards/audits/pilot-cold-start.md`, and obtain
explicit approval. A failed card must expose a retrieval or reasoning gap, not
missing instruction.

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

For this curriculum-plan-only handoff:

1. Run `flashcards deck prerequisites .` and confirm every edge resolves and the
   graph is acyclic.
2. Run `flashcards deck validate .` and confirm unique orders/identities and
   zero scheduled cards in every ordered chapter.
3. Run `git diff --check` and review the complete diff for accidental content or
   asset changes.
4. Stop for human review. Card, solution, and figure authoring require a
   separate pilot job.
