# 🌠 Living Curriculum: Computational Astrophysics (Raspberry Pi Edition)

**Goal:** A complete, open, self-directed roadmap for learning programming and computer science as applied to astrophysics — from beginner to research level — fully viable on a Raspberry Pi 3B.

---

## 🧭 Stage 0 — Orientation: Computational Thinking & Digital Literacy
**Goal:** Understand how computers and algorithms support modern astronomy.  
**Your Pi Skills:** Using the terminal, managing files, editing text in `nano` or `VS Code`, exploring Linux.

**Topics**
- What computation means in science  
- Command line & file systems  
- Markdown, text files, and data formats (CSV, FITS)  

**Resources**
- [CS50’s Understanding Technology](https://cs50.harvard.edu/technology/)  
- [Raspberry Pi Beginner Guide (PDF)](https://magpi.raspberrypi.com/books/beginners-guide)  
- [Google Crash Course on Computing (YouTube)](https://www.youtube.com/playlist?list=PL9bw4S5ePsEEr_HVQx6xt9PzCR9Y4dqLW)

**Applied Project**
Organize your learning folder tree on the Pi. Write a one-page Markdown note describing how computation powers telescopes and space missions.

---

## 🐍 Stage 1 — Foundations: Python for Scientists
**Goal:** Write simple programs to analyze and visualize data.  
**Your Pi Skills:** Run Jupyter Lab locally, use `pip` to install libraries, create small data plots.

**Topics**
- Python syntax, variables, loops, functions  
- `numpy`, `pandas`, `matplotlib`  
- Reading and writing data files  

**Resources**
- [Python for Everybody](https://www.py4e.com/)  
- [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/)  
- [Matplotlib Tutorial (Real Python)](https://realpython.com/python-matplotlib-guide/)

**Applied Project**
Download NASA Exoplanet Archive CSVs and plot planet mass vs orbital period.  
*(All doable on-device; use small datasets.)*

---

## 🔁 Stage 2 — Algorithms & Data Structures
**Goal:** Understand algorithmic logic and efficiency.  
**Your Pi Skills:** Write text-based simulations and visualize simple performance differences.

**Topics**
- Big-O notation  
- Lists, stacks, queues, trees, graphs  
- Recursion and iteration  

**Resources**
- [CS50x: Introduction to Computer Science](https://cs50.harvard.edu/x/)  
- [Visualgo.net](https://visualgo.net/)  
- [Grokking Algorithms (PDF summary)](https://edu.anarcho-copy.org/Algorithm/Grokking%20Algorithms.pdf)

**Applied Project**
Implement a 3-body simulation with naive pairwise forces; compare runtime for 3, 5, 10 bodies.

---

## 🧮 Stage 3 — Scientific Computing with Python
**Goal:** Perform numerical computation and modeling.  
**Your Pi Skills:** Optimize small simulations using vectorization (`numpy`).

**Topics**
- `scipy` for integration & ODEs  
- `astropy` for astronomical utilities  
- Units, constants, and error propagation  

**Resources**
- [Astropy Docs](https://docs.astropy.org/en/stable/#learning-resources)  
- [SciPy Lecture Notes](https://scipy-lectures.org/)  

**Applied Project**
Numerically integrate a satellite orbit around Earth and plot its trajectory.

---

## 🧰 Stage 4 — Software Engineering for Scientists
**Goal:** Build clean, shareable, reproducible code.  
**Your Pi Skills:** Use Git, GitHub CLI, virtual environments, and `pytest`.

**Topics**
- Version control (`git`)  
- Testing and documentation  
- Jupyter Notebooks and Markdown reports  

**Resources**
- [Pro Git Book](https://git-scm.com/book/en/v2)  
- [Software Carpentry Lessons](https://software-carpentry.org/lessons/)  
- [PEP8 Style Guide](https://realpython.com/python-pep8/)

**Applied Project**
Convert your orbit simulation into a GitHub repository with README, comments, and tests.

---

## ⚙️ Stage 5 — Numerical Methods & Simulations
**Goal:** Model dynamical systems using numerical algorithms.  
**Your Pi Skills:** Run longer scripts efficiently, use simple text logging, optimize array math.

**Topics**
- Finite differences, ODE/PDE basics  
- Monte Carlo simulations  
- Random number generation  

**Resources**
- [Computational Physics (Newman, free PDF)](https://www-personal.umich.edu/~mejn/cp/)  
- [TU Delft Numerical Methods for Astrophysics OCW](https://ocw.tudelft.nl/courses/numerical-methods-for-astrophysics/)  

**Applied Project**
Simulate planetary orbits using Euler vs Verlet vs Runge–Kutta methods; visualize stability and error.

---

## 📊 Stage 6 — Data Science & Lightweight Machine Learning
**Goal:** Apply data-driven methods to small astronomical datasets.  
**Your Pi Skills:** Use CPU-only ML (`scikit-learn`) and lightweight models; visualize results.

**Topics**
- Linear regression, k-means, PCA  
- Decision trees and simple neural nets  
- Model evaluation  

**Resources**
- [Kaggle Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)  
- [AstroML Docs](https://www.astroml.org/)  

**Applied Project**
Classify galaxies using a down-sampled subset of the [Galaxy Zoo dataset](https://data.galaxyzoo.org/).

---

## 🧵 Stage 7 — Efficient Computation & Parallelism
**Goal:** Use all 4 cores of your Pi efficiently.  
**Your Pi Skills:** Write parallel scripts using `multiprocessing`, `asyncio`, and Numba JIT.

**Topics**
- Vectorization and parallel loops  
- Profiling and optimization  
- Basics of cloud HPC (Google Colab for heavy workloads)  

**Resources**
- [HPC Carpentry Intro](https://hpc-carpentry.github.io/)  
- [Parallel Programming in Python (Data Science Dojo)](https://www.youtube.com/watch?v=fKl2JW_qrso)  

**Applied Project**
Parallelize your N-body simulation to simulate 100 particles; compare runtimes per core.

---

## 🌌 Stage 8 — Computational Astrophysics Methods
**Goal:** Apply specialized simulation techniques to astrophysical systems.  
**Your Pi Skills:** Run simplified versions locally; use AMUSE or REBOUND with reduced precision.

**Topics**
- N-body dynamics  
- Smoothed Particle Hydrodynamics (SPH)  
- Radiative transfer basics  

**Resources**
- [AMUSE Framework](https://amusecode.org/)  
- [Numerical Methods in Astrophysics (MIT OCW)](https://ocw.mit.edu/courses/physics/8-902-numerical-methods-in-astrophysics-spring-2004/)  

**Applied Project**
Simulate a mini star cluster (≤ 100 stars) using REBOUND or AMUSE; visualize evolution.

---

## 🧪 Stage 9 — Research Integration & Open Science
**Goal:** Conduct and share reproducible computational research.  
**Your Pi Skills:** Use `conda`/`venv`, write LaTeX in Overleaf, push projects to GitHub Pages.

**Topics**
- Reproducibility and data pipelines  
- Environment management and Docker alternatives (on Pi use Podman or Apptainer Lite)  
- Publication workflow (LaTeX, arXiv, Zenodo)  

**Resources**
- [The Turing Way](https://the-turing-way.netlify.app/)  
- [LaTeX on Overleaf Tutorials](https://www.overleaf.com/learn)  
- [Zenodo for Research Software](https://about.zenodo.org/)  

**Applied Project**
Reproduce a small open astrophysics study (e.g., orbital simulation from arXiv) using your Pi and publish the code + results.

---

## 🪐 Stage 10 — Mastery & Contribution
**Goal:** Transition from learner → research contributor.  
**Your Pi Skills:** Contribute to open-source astrophysics codebases and maintain your own repository.

**Topics**
- Open Science communities (Astropy, AMUSE, NASA Open Science)  
- Teaching and mentorship  
- Portfolio building  

**Resources**
- [NASA Open Science 101](https://nasa.github.io/Transform-to-Open-Science-Book/)  
- [Astropy Contributor Guide](https://docs.astropy.org/en/stable/development/workflow/development_workflow.html)  

**Applied Project**
Make a pull request to an Astropy submodule or publish your own Pi-friendly astrophysics tool.

---

## 🧩 Integration with Your Physics Roadmap
| Physics Stage | Computational Parallel (Pi Edition) |
|----------------|--------------------------------------|
| 0–1 Orientation / Foundations | 0–1 Python Basics |
| 2–4 Classical & EM | 2–5 Algorithms & Numerical Methods |
| 5–7 Quantum & Relativity | 6–8 Data Science & Simulations |
| 8–10 Research & Graduate Work | 8–10 Computational Astrophysics & Open Science |

---

### ⚙️ Suggested Raspberry Pi Setup
- **OS:** Raspberry Pi OS (64-bit Bookworm)  
- **Python env:** `sudo apt install python3-pip python3-venv`  
- **Key packages:**  
  ```bash
  pip install numpy scipy matplotlib pandas astropy jupyterlab scikit-learn numba rebound
