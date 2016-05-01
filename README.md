# Oyster
©2016 feisty2, Oyster Python Module for VapourSynth
## License
LGPL v2.1
## Description
Oyster is a top class de-noising filter against compression artifacts in terms of quality, it is outrageously slow and deadly expensive at computational costs.
Each pixel will be restored by the weighted average of its neighbors, weights generated by Block-Matching and Pixel-Matching algorithms, spatially and temporally.
It is designed for photographic videos, but works on CGI like cartoons and anime also.
## Requirements
NNEDI3
KNLMeansCL
BM3D
FMTConv
MVTools (floating point ver)
