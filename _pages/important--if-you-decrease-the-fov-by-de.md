---
title: "IMPORTANT: If you decrease the FOV by decreasing the matrix size in the phase encoding direction by 50%, then what does that do to your image acquisition time?"
---
Decreases it. 

Your voxel stays the same size b/c both FOV and matrix changed the same. Therefore, the number of measurements you need (phase encoding steps) decreases by 50% and so does scan time.

* Note that your SNR will decrease to 70% (SNR is proportional to the square root of # measurements)

* Truncation Gibbs will increase because high spatial frequencies are not as well sampled when the number of phase encoding steps is reduced

