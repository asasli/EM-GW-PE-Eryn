# EM-GW PE with Eryn
This notebook demonstrates how we can perform parameter estimation (PE) for a **GB** (WDB) source with [Eryn](https://github.com/mikekatz04/Eryn). We will simulate the GW signal from a WDB using [GBGPU](https://github.com/mikekatz04/GBGPU) package and then, the light curve via `ellc` package. We will demonstrate a simple example of performing PE with a joint EM-GW likelihood.

More information:

- Eryn documentation [here](https://mikekatz04.github.io/Eryn/index.html).
- GBGPU documentation [here](https://mikekatz04.github.io/GBGPU/).
- Part of this notebook has been writen based on [this](https://github.com/asasli/hyperbolic_likelihood_filter) repo.

Please download the [data](https://github.com/asasli/EM-GW-PE-Eryn/blob/main/data_gbgpu.npz) 📂 and save it in the same directory with the notebook!

> Notes: `conda activate -n acme_eryn_env` and install **GBGPU** for CPU-only version `pip install gbgpu`

----------------------------------------

Argyro Sasli $^\dagger$, Nikos Karnesis $^\ast$ 

$^\dagger$ University of Minnesota

$^\ast$ Aristotle University of Thessaloniki

(Nov 2025)

For the course of "ACME hands-on sessions" 
