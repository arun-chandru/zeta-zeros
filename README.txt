COMPENSATED GRAM CORRECTIONS FOR ZERO COUNTS OF THE RIEMANN ZETA FUNCTION
R. Arun Chandru
10 September 2026

CONTENTS

manuscript.tex       Main article, with all finite and analytic deductions.
literature.tex       Public-prior-art comparison, included by manuscript.tex.
bibliography.tex     Main bibliography, included by manuscript.tex.
supplement.tex       Independently readable local certification supplement.
verification/        Self-contained Python verification sources, generated
                     scalar data, completed receipts, requirements and license.

The publication archives contain only these necessary sources and their
execution evidence. Internal research notes and earlier manuscript versions
are not proof dependencies and are not part of the publication archives.

BUILDING THE ARTICLES

Use a current LaTeX distribution with amsart, fontenc, lmodern, geometry,
amsmath, amssymb, mathtools, booktabs, microtype, hyperref and xurl.
In the article source directory, run either:

    latexmk -pdf manuscript.tex
    latexmk -pdf supplement.tex

or run pdflatex on each source until references and contents stabilize.
Tectonic may also be used. No shell escape or external data download by the
article is required. A LaTeX installation may need to install standard
packages/fonts. The main article and supplement have separate bibliographies.

VERIFICATION

Read verification/README.md for exact commands, dependencies, finite resource
limits, and the logical role of each program. Python-flint is needed for
whole-cell table generation and the seven-point covers. The rational scalar,
gate, and triple arithmetic uses Python's standard library once the six-mode
table has been generated. The table generator is supplied.

Every replay must use a fresh receipt filename: existing receipts are never
overwritten. A timeout or an unresolved cell is not a successful proof.
The archived receipts identify actually executed sources; the manifest gives
SHA-256 byte identities, not mathematical guarantees. Matching ordinary and
optimized Python executions is a consistency check, not an independent
arithmetic proof or external peer review.

RESULT AND SCOPE

The main article gives unconditional global inequalities for five carefully
distinguished counting statistics. It proves explicit improvements over named
same-statistic union and low-multiplicity formulas. It does not claim the best
simple-critical bound, the best distinct-zero bound, or worldwide priority.
The separately qualified short-height statements use a cited recent preprint;
the full-height conclusions do not depend on that input.

The supplement establishes the two main seven-point local inequalities and,
for a different six-mode thirteen-point problem, the all-long region and all
twelve one-short regions. Both interior placements are included. Configurations
with two or more short gaps remain unresolved. The partial thirteen-point
result supplies no new global zero-count bound.

