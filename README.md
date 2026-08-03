<!-- Source of the published repository's README. Edited here and copied by
     ../scripts/deploy-landing.sh; editing the copy inside deploy-ccn2026/ is what puts the two out of
     step. This file is published, so it addresses a visitor to the repository, not a maintainer. -->
# CCN 2026 poster — supporting material

Landing page for the QR code on the CCN 2026 poster *How do RNNs encode mixtures?* by Esther
Poniatowski and Claire Sergent (Integrative Neuroscience and Cognition Center, CNRS UMR 8002,
Université Paris Cité).

Published at <https://esther-poniatowski.github.io/ccn2026/>.

## Contents

| Path | Role |
| --- | --- |
| `index.html` | The page the printed code resolves to: an index of the supporting material, and the reference list itself |
| `supplement.pdf` | The seven numbered points the poster's badges refer to |
| `abstract.pdf` | The camera-ready extended abstract |
| `.nojekyll` | Stops GitHub from reinterpreting any path through Jekyll |

The poster itself is added here once a downsampled copy exists.

## Deployment target, not source

This repository holds published output. The page is authored in the poster project, beside the
supplement whose numbering it mirrors, and copied here by a deployment script that also refuses to
publish a link whose target file is absent. Editing `index.html` in place would put the numbered list
out of step with the supplement it indexes, so changes belong upstream.

## Stability

The URL is printed on the poster and cannot be corrected afterwards. Neither the repository name nor
the path of `index.html` may change.
