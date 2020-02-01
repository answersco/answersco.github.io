---
title: "IMPORTANT: In single spin echo, what does &quot;sampling the echo&quot; refer to?"
---
The number of frequency encoding steps. 
For a 128 x 256 matrix, you'll want 128 phase encoding steps (to decrease time of scan) and 256 frequency encoding steps. Therefore you &quot;sample the echo 256&quot; times.

- You fill a line of k-space by sampling the echo 256x; and then perform 128 repetitions to fill in the rest of the matrix (e.g. 128 phase encoding steps)

