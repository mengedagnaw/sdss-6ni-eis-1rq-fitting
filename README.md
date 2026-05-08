# SDSS 6Ni EIS 1RQ Fitting

Python workflow for fitting electrochemical impedance spectroscopy (EIS) data from 6 wt.% Ni-added super duplex stainless steel using a single-time-constant equivalent circuit model.

## Equivalent circuit

```text
Rs - (Q || R)
```

where:

- `Rs` is the solution resistance.
- `R` is the polarization or charge-transfer resistance.
- `Q` is the constant phase element (CPE).
- `(Q || R)` is the parallel CPE–resistance branch.

## Purpose

This repository contains scripts and figures for 1RQ equivalent-circuit fitting of EIS spectra from 6 wt.% Ni-added SDSS conditions.

The workflow includes:

- Nyquist and Bode visualization
- nonlinear least-squares EIS fitting
- comparison of fitted parameters
- residual analysis
- figure generation for reporting/publication

## Repository structure

```text
sdss-6ni-eis-1rq-fitting/
├── README.md
├── scripts/
└── figures/
```

## Notes

- Fitted EIS parameters should be interpreted together with residual structure and physical plausibility.
- A good numerical fit does not uniquely validate the equivalent circuit.
- Raw or unpublished EIS data should not be uploaded unless public release is intended.
