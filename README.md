# 📚 Gaussian Process Reading Group

Welcome to the **Gaussian Process (GP) Reading Group**! This repository hosts the syllabus, reading materials, notes, and code examples for our 8-week journey through the theory and application of Gaussian Processes.

Our goal is to bridge the gap between the foundational machine learning perspective (Rasmussen & Williams), the spatial statistics view (Stein, Cressie), and modern applications in Bayesian optimization and computer experiments.

---

## 🗓️ 8-Week Reading Plan

We follow a structured 8-week schedule designed to build intuition from basics to advanced topics.

| Week | Topic | Core Reading | Key Concepts |
| :--- | :--- | :--- | :--- |
| **1** | **Bayesian Regression & GP Basics** | R&W Ch. 2 | GP prior/posterior, predictive mean/variance |
| **2** | **Kernels & Covariance Functions** | R&W Ch. 4 | SE, Matérn, periodic kernels, smoothness |
| **3** | **Hyperparameter Learning** | R&W Ch. 5 | Marginal likelihood, evidence maximization |
| **4** | **GP Classification** | R&W Ch. 3 | Laplace approx, EP, non-Gaussian likelihoods |
| **5** | **Computation & Sparse GPs** | R&W Ch. 8 | Inducing points, variational inference, scaling |
| **6** | **Kriging & Spatial Statistics** | Stein (Selected) | Variograms, stationarity, spatial prediction |
| **7** | **Design & Computer Experiments** | Gramacy / Santner et al. | Latin hypercube, emulation, calibration |
| **8** | **Special Topic** | Garnett | Bayesian Optimization |

> **Note:** "R&W" refers to *Rasmussen & Williams (2006)*.

---

## 📖 Core Syllabus

### 1. The Main Textbook
*   **Gaussian Processes for Machine Learning** (Rasmussen & Williams, 2006)
    *   *Role:* The definitive guide for ML-focused GPs.
    *   *Chapters:* 2, 3, 4, 5, 8.
    *   [Link to Book](http://www.gaussianprocess.org/gpml/)

### 2. The Practical Companion
*   **Surrogates** (Gramacy, 2020)
    *   *Role:* Modern applied methodology, design, and optimization.
    *   *Focus:* Scalable GPs, computer experiments, Bayesian optimization.
    *   [Link to Book](https://www.rbggramacy.com/surrogates/)

### 3. The Spatial Statistics View
*   **Interpolation of Spatial Data** (Stein, 1999)
    *   *Role:* Rigorous theory of kriging and covariance modeling.
    *   *Focus:* Matérn functions, asymptotic properties, BLUP.
*   **Statistics for Spatial Data** (Cressie, 1993) & **Statistics for Spatio-Temporal Data** (Cressie & Wikle, 2011)
    *   *Role:* Broad background on random fields and hierarchical modeling.

### 4. Computer Experiments & UQ
*   **The Design and Analysis of Computer Experiments** (Santner, Williams & Notz, 2018)
    *   *Role:* GP modeling for deterministic simulators and engineering.
    *   *Focus:* Experimental design, model validation, calibration.

### 5. Modern Probabilistic ML Context
*   **Probabilistic Machine Learning: Advanced Topics** (Murphy, 2023)
    *   *Role:* Broader context on latent variables and approximate inference.
    *   *Focus:* Variational inference, sparse approximations.

---

## 🔍 Supplementary & Advanced Texts

### Preparatory Background
*   **Pattern Recognition and Machine Learning** (Bishop, 2006): Quick bridge into Bayesian regression and kernels.
*   **Learning with Kernels** (Schölkopf & Smola, 2002): Deep dive into RKHS and kernel theory.

### Specialized Extensions
*   **Bayesian Optimization** (Garnett, 2023): The standard for sequential decision-making and acquisition functions.
*   **Fundamentals of Nonparametric Bayesian Inference** (Ghosal & van der Vaart, 2017): Mathematical theory of GP priors and posterior contraction.
*   **Random Fields and Geometry** (Adler & Taylor, 2007): Advanced geometry of sample paths and excursion sets.

---

## 📝 Papers & Code
*Coming soon!* We will add a list of seminal papers and Jupyter notebooks corresponding to each week's topic.

## 🔗 Resources
*   **Collaborative Notes (Overleaf):** [View/Edit Notes](https://www.overleaf.com/7823943244fhhdpbqnkjbb#3f1c67)
*   **GPML Toolbox:** [Official Code](http://www.gaussianprocess.org/gpml/code/matlab/doc/)
<!--*   **GPyTorch:** [PyTorch Library](https://github.com/cornellius-gp/gpytorch)
*   **Scikit-learn GPs:** [Documentation](https://scikit-learn.org/stable/modules/gaussian_process.html)
-->
---

## 🤝 How to Contribute
1.  **Fork** this repository.
2.  Add your notes or code examples to the `/notes` or `/code` directory.
3.  Submit a **Pull Request** with the week number in the title (e.g., "Week 2: Matérn Kernels").

## 📅 Meeting Details
*   **Time:** [Insert Time]
*   **Location:** Zoom Link
<!-- *   **Contact:** [Insert Organizer Email/Slack]
-->

---

*Happy Reading!* 🚀
