---
title: "What artifact occurs when the FOV in the phase-encoding direction is smaller than the anatomy that is being imaged?"
---
Aliasing (&quot;Wrap-Around&quot;) Artifact&#8594; appears as an anatomical structure, from outside the FOV, that wraps around to the other side of the image.
This wrap-around&#8594; predominantly occurs along the phase-encoding direction &#8594; for this and other reasons, the phase-encoding direction is often chosen along the short axis of the tissue being imaged.
Origin&#8594; FOV in the phase-encoding direction is smaller than the anatomy that is being imaged.

Method to lessen the artifact: exchange the frequency-encode direction with the phase-encode direction.
In general, if this is a concern, one should choose the short axis of the body in the image to be the phase-encoding direction.
Aliasing can be mitigated by ensuring that the FOV properly contains the tissue that has been excited by the sequence.
Alternatively, spatial saturation bands can be applied to null the signal from tissue outside the FOV.

