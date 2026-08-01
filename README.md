# India Space Academy Internship Projects — Data-Driven Astronomy

This repository contains two projects completed during the **India Space Academy (ISA) — Astronomy & Astrophysics Internship**, part of the ISA Summer School, organized by the Department of Space Education, India Space Academy. Both projects apply observational astronomical data and Python-based statistical analysis to estimate fundamental physical quantities: the expansion rate of the Universe, and the mass of a galaxy cluster.

## 📁 Repository Structure

| Notebook | Project |
|---|---|
| `ISA_Cosmo_Parameter.ipynb` | Supernova Cosmology — Hubble Constant & Density Parameter |
| `ISA_Dynamical_mass.ipynb` | Dynamical Mass of a Galaxy Cluster |

---

## Project 1: Constraining the Hubble Constant ($H_0$) and Density Parameter ($\Omega_m$) Using Supernovae (Type Ia) from Pantheon+SH0ES

### 📌 Objective
The main objective of this project is to estimate key cosmological parameters using observational data from Type Ia supernovae, based on the **Pantheon+SH0ES** dataset.
* Estimate the value of the **Hubble constant ($H_0$)** and the **matter density parameter ($\Omega_m$)** by fitting the distance modulus–redshift relation (Hubble diagram).
* Investigate how fixing $\Omega_m$ affects the fitted value of $H_0$.
* Explore the age of the Universe derived from the best-fit parameters.
* Assess the quality of the cosmological fit by analyzing residuals.
* Study redshift-dependent differences in $H_0$ by splitting data into low-redshift and high-redshift subsets.
* Compare findings with the 2018 Planck results to discuss the current status of the **Hubble tension**.

### 📊 Dataset
The **Pantheon+SH0ES** dataset — one of the most comprehensive compilations of Type Ia supernova observations available, combining the original Pantheon sample with SH0ES calibrations. Provides precise redshift and photometric data for **1,500+ Type Ia supernovae**, spanning $z \sim 0.001$ to $z \gtrsim 1$.

---

## Project 2: Estimating the Dynamical Mass of a Galaxy Cluster Using SDSS Spectroscopic Data

### 📌 Objective
The main objective of this project is to estimate the **dynamical mass** of a galaxy cluster using spectroscopic redshift and photometric data from the Sloan Digital Sky Survey (SDSS DR16), and to test it against the cluster's **luminous (stellar) mass** to probe the presence of dark matter.
* Identify cluster member galaxies from a field of candidates using a $3\sigma$ redshift-clipping criterion.
* Determine the systemic cluster redshift and characteristic velocity dispersion via the relativistic Doppler formula.
* Estimate the physical size (diameter) of the cluster from its angular extent and angular diameter distance.
* Apply the virial theorem to compute the cluster's **dynamical mass**.
* Estimate the cluster's **luminous mass** from SDSS photometry using the Bell et al. (2003) color–mass-to-light relation.
* Compare dynamical vs. luminous mass to quantify the fraction of the cluster's mass that is non-luminous (dark matter).

### 📊 Dataset
Spectroscopic and photometric data queried from the **SDSS DR16 Skyserver SQL search tool**, for galaxies (`type = 3`) within a 10-arcminute field centered at (RA, Dec) = (258.1294°, 64.0926°), restricted to spectroscopic redshifts $0.05 < z < 0.20$. Key columns used: `objid`, `specz`, `ra`, `dec`, `proj_sep`, `gmag`, `rmag`.

---

## 🛠️ Tech Stack & Skills
* **Programming Language:** Python
* **Environment:** Jupyter Notebook
* **Key Libraries:** `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy` (curve fitting & optimization), `astropy` (constants, units, cosmology)
* **Domain:** Observational Cosmology, Galaxy Dynamics, Data-Driven Astronomy, Astrophysics

## 🤝 Acknowledgments
Both projects were developed as part of the **India Space Academy — Astronomy & Astrophysics Internship**, organized by the Department of Space Education, India Space Academy (ISA), New Delhi.
