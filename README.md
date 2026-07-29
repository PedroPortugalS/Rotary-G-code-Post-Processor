# Rotary G-code Post-Processor

A Python-based post-processor that enables indexed 4-axis CNC machining on standard GRBL-controlled machines without requiring firmware modifications or hardware retrofits.

The software transforms conventional XZ-plane G-code into indexed rotary toolpaths, allowing low-cost desktop CNC systems to perform discrete rotary machining through software alone.

---

## Associated Publication

This repository contains the implementation accompanying the publication:

**Planar-to-Rotary G-code Transformation Via Post-Processing for Discrete 4-Axis Machining**

Pedro Portugal, Damian D. Venghaus, Diego Lopez

*International Journal of Computer Aided Manufacturing*, Vol. 12, Issue 1.

An earlier preprint of this work is also available:

**A Software-Only Post-Processor for Indexed Rotary Machining on GRBL-Based CNCs**

https://arxiv.org/abs/2509.11433

---

## Features

- Converts XZ-plane G-code into indexed rotary machining instructions
- Compatible with standard GRBL-based CNC controllers
- No firmware modifications required
- Automatic angular indexing calculation
- Desktop graphical user interface
- Browser-based web interface
- Intended for educational, prototyping, and makerspace applications

---

## Usage

1. Load an XZ-plane G-code file.
2. Enter the stock diameter and overlap factor.
3. Generate the indexed rotary G-code.
4. Execute the generated toolpath on a GRBL-based CNC machine configured for indexed rotary machining.

---

## Citation

If this software contributes to your research, please cite:

```bibtex
@article{Portugal2026,
  title={Planar-to-Rotary G-code Transformation Via Post-Processing for Discrete 4-Axis Machining},
  author={Portugal, Pedro and Venghaus, Damian and Lopez, Diego},
  journal={International Journal of Computer Aided Manufacturing},
  volume={12},
  number={1},
  year={2026}
}
```

---

## License

This project is released as open-source software to support research, education, and engineering development.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17211808.svg)](https://doi.org/10.5281/zenodo.17211808)
