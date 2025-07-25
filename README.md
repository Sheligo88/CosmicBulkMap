# CosmicBulkMap

**Resolving the Local Dipole Anisotropy**  
**Authors:** Iván Sheligo, Gemini (Google), ChatGPT (OpenAI)

Repository: [github.com/ivansheligo/CosmicBulkMap](https://github.com/ivansheligo/CosmicBulkMap)  
*(Recuerda actualizar este enlace si lo cambias)*

---

## Project Goal

This repository contains the full analysis pipeline and results for the paper  
**"Observational Resolution of Local Dipolar Anisotropy"**  
(Sheligo, Gemini, & ChatGPT 2025, to appear on arXiv).

Our objective is to perform a robust, independent analysis of the cosmic bulk flow by measuring the dipolar anisotropy in the Hubble–Lemaître diagram using two of the most comprehensive and recent datasets available:

- **Pantheon+:** A compilation of Type Ia Supernovae.
- **CosmicFlows-4:** A catalog of peculiar velocities.

We provide all necessary code, data links, and explanatory notebooks to ensure our analysis is **transparent, reproducible, and extensible** by the scientific community.

---

## Getting Started: A 5-Minute Demo

The best way to understand our methodology is to run the demonstration notebook.  
It walks you through the core concepts of the analysis using a small, manageable dataset.

- 📓 **Open the Demo Notebook:**  
  `notebooks/example_analysis.ipynb`

This notebook will show you how to:
- Load and visualize cosmological data.
- Understand the physically-motivated model for a dipole anisotropy.
- Generate a sky map of the bulk flow signal (the "CosmicBulkMap").

---

## How to Contribute

We welcome contributions from the community!  
Whether you want to report a bug, suggest an improvement, or add a new analysis module, please feel free to:

- **Open an Issue:** Discuss the change you would like to make.
- **Fork the Repository:** Create your own copy of the project.
- **Create a Pull Request:** Submit your changes for review.

Please check our **Contribution Checklist** inside the demo notebook for specific ideas on where you can help.

---

## Core Dependencies

The analysis relies on the standard Python scientific stack:

- `numpy`
- `pandas`
- `matplotlib`
- `astropy`
- `healpy`

A `requirements.txt` file will be provided for easy installation via pip.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Citation

If you use this code or the results from our analysis in your research, please cite our paper:

```bibtex
@article{Sheligo2025,
  author  = {Sheligo, Iv{\\'a}n and Gemini and ChatGPT},
  title   = {Observational Resolution of Local Dipolar Anisotropy},
  journal = {arXiv e-prints},
  year    = {2025},
  eprint  = {arXiv:XXXX.XXXXX}
}

