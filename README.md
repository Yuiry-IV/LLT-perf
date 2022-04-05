# LLT-perf

Lucas–Lehmer test (LLT) is a primality test performance

| exp\CPU |   i7-7700HQ  | i7-3610QM   |  i5-9600K    | Threadripper 3970X 32-Core |
|---------|--------------|-------------|--------------|----------------------------|
|   44497 |              |   3.29415 s.|   1.74971 s. |                            |
|   86243 |              |  16.2306 s. |   8.61329 s. |                            |
|  110503 |   20.0041 s. |  28.6329 s. |  15.0376 s.  |    14.9083 s.              |
|  132049 |   30.6906 s. |  44.3357 s. |  23.1764 s.  |    22.8448 s.              |
|  216091 |  104.504 s.  | 146.499 s.  |  77.9854 s.  |    75.6733 s.              |
|  756839 | 1965.42 s.   |             |              |  1154.37 s.                |
|  859433 | 2091.52 s.   |             |              |  1372.37 s.                |
| 1257787 |              |             |              |  0.866907 h.               | 
| 1398269 |              |             |              |  1.12004 h.                |
| 2976221 |              |             |              |  5.11919 h.                |
| 3021377 |              |             |              |  5.52554 h.                |
| 6972593 |              |             |              |  39.2661 h.                |