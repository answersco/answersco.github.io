---
title: "What artifact occurs when the # of samples in k-space (ensembles) is too small?"
---
Gibbs (truncation) artifact.
Gibbs artifact&#8594; appears as alternating bright and dark lines on the MRI images that are parallel to an adjacent border exhibiting an abrupt change in signal intensity. Can be in phase- and/or frequency-encoding direction.
Origin&#8594; the number of samples in k-space (ensembles) is too small. Fourier-based imaging technique leads to image errors near sharp boundaries.

Lessen or eliminate the artifact:
One can remediate the effect by specifying more phase encodings and more samples acquired during frequency encoding (i.e. increase matrix) &#8594; this &#8595; the spacing between artifactual lines.
Can also use pre- or post-reconstruction image filtration

