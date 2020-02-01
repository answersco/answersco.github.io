---
title: "How does readout work?"
---
One readout (or one phase-encode) = one line of k-space
The process repeats after a time (TR), with different phase encoding.
K-space is filled row-by-row with each interval TR&#8594; after many readouts, k-space is filled.
Inverse Fourier transform&#8594; converts k-space to image.
&quot;Fast&quot; sequences (e.g. fast spin echo) &#8594; may fill several lines of k-space per TR
&quot;Non-cartesian&quot; sequences&#8594; may fill k-space in patterns other than row by row (e.g. radial sequences&#8594; fill k-space as a set of rows passing through the center of k-space, in a star-like pattern).
Image sequences may leave some portion of k-space empty to save imaging time (e.g. &quot;partial fourier&quot; techniques, parallel imaging, etc.)

