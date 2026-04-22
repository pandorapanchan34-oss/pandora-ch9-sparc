# Pandora Theory — Chapter 9: Information Saturation in Galaxy Outer Regions

Zero-free-parameter model for galaxy rotation curves.  
Independent verification against 125 SPARC galaxies (Lelli+2016).

## Key Results

| Metric | Value |
|--------|-------|
| Outer-region Median MAE | **4.08%** |
| Free parameters | **0** |
| Saturation ratio (observed) | 0.8365 |
| Saturation ratio (theory: 5/6) | 0.8333 |
| Deviation | 0.38% |
| n=3 saturation detections | 72 / 125 |
| n=2 saturation detections | **0** |

## Files

- `pandora_ch9_v3.pdf` — Full paper (Japanese)
- `pandora_outer_sparc.jsx` — Interactive visualization (125 galaxies)

## Data Source

SPARC database: Lelli+2016  
https://astroweb.cwru.edu/SPARC/

## Model

V_obs(r) = V_flat × (1 − TAU)^ζ(r)  
ζ(r) = max(0, I(r)/I* − 1)  
I(r) = K₄ · ln(2) · (r / unit)^τ_eff  

Constants (no free parameters):  
- K₄ = 24 (D₄ lattice contact number)  
- TAU = 9/(24π) ≈ 0.11937  
- I* = 9π ≈ 28.274  
- Saturation threshold G = 5/6 (algebraically derived)

## Status

Chapter 9 of 10. External feedback welcome.  
Author: @pandorapanchan1
