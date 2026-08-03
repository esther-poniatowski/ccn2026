<!-- Source of the published repository's README. Edited here and copied by
     ../scripts/deploy-landing.sh; editing the copy inside deploy-ccn2026/ is what puts the two out of
     step. IT ADDRESSES A READER, NOT A MAINTAINER: how the page is built and deployed belongs to
     ../qr-strategy.md, and nothing about that machinery is repeated here. -->
# How do RNNs encode mixtures? One network yields distinct geometries

Supporting material for the poster presented by Esther Poniatowski and Claire Sergent at the 9th
Conference on Cognitive Computational Neuroscience, New York, 2026 (Integrative Neuroscience and
Cognition Center, CNRS UMR 8002, Université Paris Cité).

Read it at <https://esther-poniatowski.github.io/ccn2026/>.

## The work

Natural inputs are often superimpositions of simpler components, such as overlapping gratings in
vision or mixed voices in audition. For such mixtures, recordings report three response geometries:
the component responses combine in proportion to their input strengths, or one component is favoured
over the other, or a pattern emerges that neither component alone elicits. Divisive normalization
captures the phenomenology of the first two, without identifying the network mechanism behind them and
without expressing emergence.

This theoretical study analyses a recurrent-network model and derives the circuit property that
selects each geometry: the amplification profile across the network's principal directions. A uniform
profile leaves the mixture aligned with the proportional sum, an uneven profile rotates the response
inside the plane the components span, and three or more driven directions carry it out of that plane.
One network therefore produces all three geometries as the input varies, with no change in synaptic
weights.

## Contents

| Path | Role |
| --- | --- |
| `index.html` | The page the poster's QR code resolves to: the result in brief, the material below, and the reference list |
| `supplement.pdf` | Seven numbered points, matching the numbered badges printed on the poster |
| `abstract.pdf` | The extended abstract, licensed under CC BY 4.0 |

The poster itself is added once a downsampled copy exists.

## Correspondence

Esther Poniatowski — <esther.poniatowski@ens.psl.eu> —
[LinkedIn](https://www.linkedin.com/in/esther-poniatowski/).
[Sergent Consciousness Lab](https://sergent-consciousness-lab.u-paris.fr/).

The page is authored in the project that produced the poster and copied here, so corrections belong
upstream rather than in this repository.
