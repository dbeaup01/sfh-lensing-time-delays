# sfh-lensing-time-delays

Reproducible Jupyter notebooks for computing strong gravitational-lensing
time delays in the Spacetime Flow Hypothesis (SFH) using observationally
constrained lens models.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dbeaup01/sfh-lensing-time-delays)

---

## Overview

This repository contains fully reproducible analysis notebooks supporting
the strong-lensing time-delay study presented in the associated Zenodo
preprint.

In the Spacetime Flow Hypothesis (SFH), gravitational time delays arise from
local resistance to the flow of proper time rather than spacetime curvature.
Each notebook applies the same SFH time-delay formalism to a *single observed
strong-lensing system*, using that system’s published observational inputs.

The emphasis of this repository is **clarity, independence, and
reproducibility**, not code reuse or optimization.

---

## Structure

This repository contains **one Jupyter notebook per strong-lensing system**.
Each notebook applies the same SFH lensing time-delay framework to a
single observed lens, using that system’s published astrometry, redshifts,
and environment estimates.

- `SFH_Lensing_Template.ipynb`  
  Canonical analysis template used for all lenses.

- `SFH_Lensing_<SYSTEM>.ipynb`  
  Self-contained analysis for each individual lens.

This design avoids shared state between systems and ensures that each
result is **independently reproducible**.

---

## Data policy

- No proprietary or modified datasets are included in this repository.
- All observational inputs (astrometry, redshifts, time delays, environment
  estimates) are taken from publicly available lensing analyses and are
  documented within each notebook.
- Users are not required to download or manage external datasets beyond
  what is explicitly requested in each notebook.

---

## How to run

1. Click the **Open in Colab** badge above.
2. Open any individual lens notebook.
3. Run the cells sequentially from top to bottom.

Each notebook is designed to run independently and does not depend on
outputs from other systems.

---

## Related work

- *Strong Gravitational Lensing Time Delays in the Spacetime Flow Hypothesis*  
  Zenodo preprint (2026)

This repository serves as the **computational companion** to that paper.

---

## License

MIT License
