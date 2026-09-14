## Overview

This repository presents a functional verification case study of the open-source Python package *benford_py*, examining its state five years after its final release in June 2021. Benford's Law describes the expected frequency distribution of leading digits in naturally occurring datasets—a principle with applications across finance, accounting, forensics, and fraud detection. The *benford_py* package provides statistical tools to test whether datasets conform to this principle.

The study evaluates whether *benford_py* continues to execute its documented workflow correctly within a modern Python environment, despite minimal maintenance since its v0.5.0 release. Using contemporary, unpinned dependencies (pandas 3.0.5, NumPy 2.5.3, and Matplotlib 3.11.2), the analysis confirms that the core workflow remains functional and produces expected first-digit distributions. However, the test suite encounters failures due to NumPy 2.0 incompatibilities, and undocumented warnings appear during plotting operations. These findings demonstrate that while the package retains analytical utility, its testing infrastructure requires critical maintenance.

## Significance as a Historical Record

This case study holds broader significance beyond the specific findings about *benford_py*. It serves as a detailed historical snapshot of a single GitHub repository in the present moment, documenting how unmaintained scientific software ages in practice. By providing a granular examination of one open-source project—its preserved functionality, accumulated technical debt, and points of failure—this work creates a reference point for understanding the lifecycle of GitHub repositories in the scientific Python ecosystem.

Rather than drawing generalizations about all unmaintained packages, this approach acknowledges the particular nature of software history: each repository has its own trajectory, dependencies, and maintenance story. Five years from now, this record will offer insights into how the Python ecosystem evolved and how a single project navigated (or did not navigate) that evolution. In this way, the case study functions as both a technical evaluation and a form of software archaeology—preserving evidence of what works, what breaks, and why, at a specific moment in time.

---

Suggested citation:
> Torane, H. "Functional Verification of Benford_py Five Years After Its Release". Preprint, Zenodo, September 14, 2026. https://doi.org/10.5281/zenodo.22743722.
