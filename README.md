# Astrostatistics Simulations

This repository contains my original simulations and model explorations, inspired by the **Astrostatistics Summer School (2025)** hosted by **Penn State University**. The program introduced me to some of the statistical techniques used in analyzing astronomical data — particularly under uncertainty and noise.

**"The cosmos is full of signals. Statistics helps us listen better."**

This repo is a reflection of my post-course experimentation using:
- **Bayesian inference**
- **MCMC sampling**
- **Signal detection in time series**

⚠️ **Note**: No official or copyrighted course content is distributed here.  
All code and content in this repository is independently created or sourced from public domain references.

---

## 💡 Contents in this repository

| Folder / File | Description |
|---------------|-------------|
| [`noisy_light_curve_simulation.ipynb`](https://github.com/TimeB1729/noisy_light_curve_simulation) | Simulating noisy stellar light curves using sinusoidal and Gaussian processes |
| [`bayesian_inference_for_periodic_signals.ipynb`](https://github.com/TimeB1729/posterior_inference_for_periodic_signals) | Posterior inference for periodic signals embedded in noise |
| [`mcmc_sampling_playground.ipynb`](my_notebooks/mcmc_sampling_playground.ipynb) | Experimenting with different MCMC samplers on simulated data |

Each notebook contains clear markdown explanations and visualizations.

---

## 🔭 Inspirations & References

These simulations were deeply influenced by the following **public resources**:

- [🧿 Prof. Tom Loredo's "Introduction to Bayesian Analysis"](https://github.com/tloredo/SummerSchool2025-IntroBayes)
- [🧮 Murali Haran’s blog on "An application of MCMC sampling"](https://murali-haran.github.io/MCMCtut/MCMC.html)

---

## ✍️ My Reflections

This repository marks a pivotal point in my journey from statistics to astrophysics. I began to see the cosmos not just as a physical entity, but as a source of noisy signals begging for probabilistic interpretation. Bayesian methods don't just *predict* — they *infer*, *update*, and *adapt* in the face of uncertainty.

It also made me curious about applying similar tools in domains like **financial markets**, **biomedical signal processing**, and **anomaly detection in time series** — where the art of "seeing through the noise" is just as vital.

---

## ⚙️ Running the Notebooks

All notebooks are written in Python and run on `Jupyter`. You can install the required packages with:

```bash
pip install -r requirements.txt
