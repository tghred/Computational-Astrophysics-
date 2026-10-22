


# 🌌 Computational Astrophysics: An Introduction to Modern Astrophysics (Python)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 About This Repository
This repository is a collection of Jupyter Notebooks designed to bridge the gap between theoretical astrophysics and computational data science. 

Based on the textbook **"An Introduction to Modern Astrophysics" by Bradley W. Carroll and Dale A. Ostlie**, this project translates the complex mathematical equations of celestial mechanics, stellar astrophysics, and cosmology into executable, reproducible Python code.

## 🎯 Why This Project?
As a Data Engineer and Data Scientist with a strong passion for astrophysics, I realized that reading equations is not enough. To truly understand the universe, we must **simulate it, model it, and analyze the data it generates**. 

Whether you are a physics student looking to learn Python, or a data scientist fascinated by the cosmos, these notebooks will help you visualize abstract concepts, fit models to real astronomical data (like Gaia and SDSS), and build computational pipelines.

## 🛠️ Tech Stack
*   **Core:** Python 3.9+
*   **Mathematics & Data:** `NumPy`, `SciPy` (Optimization & Curve Fitting), `Pandas`
*   **Visualization:** `Matplotlib`, `Seaborn`
*   **Astronomy (Optional):** `Astropy` (for FITS files and celestial coordinates)

## 📂 Repository Structure
*(This structure will grow as I progress through the book)*

*   **Part I: The Tools of Astronomy**
    *   `Ch03_Celestial_Mechanics`: Kepler's Laws, Elliptical Orbits, and Projectile Motion.
*   **Part II: The Nature of Stars**
    *   `Ch07_Stellar_Properties`: Stellar Parallax, Magnitudes, and Blackbody Radiation.
    *   `Ch08_The_Sun`: Stellar Structure and Energy Transport.
*   **Part III: Galaxies and the Universe**
    *   *(Coming Soon)*

## ✨ Highlighted Projects & Notebooks

### 1. Proving Kepler's First Law (Ellipse Fitting)
*   **Concepts:** Eccentricity, Polar Coordinates, Semi-major/minor axes.
*   **Data Science Application:** Simulating noisy astronomical data points (like Gaia DR3) and using `scipy.optimize.least_squares` to find the best-fit elliptical orbit, proving that planets travel in ellipses with the Sun at one focus.
*   **Notebook:** `Ch03_Kepler_Ellipse_Fitting.ipynb`

### 2. Projectile Motion in a Flat Space
*   **Concepts:** Initial velocity, Gravity, Range of a projectile.
*   **Data Science Application:** Writing reusable Python functions to calculate the range of a projectile and visualizing the trajectory using `matplotlib`.
*   **Notebook:** `Ch03_Projectile_Motion.ipynb`

### 3. (Upcoming) Fitting Real Gaia DR3 Data
*   **Concepts:** True Anomaly, Parallax, Proper Motion.
*   **Data Science Application:** Building a data pipeline to ingest real GAIA data, clean it, and apply the orbital equations to extract physical parameters.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Computational-Astrophysics-Python.git
```

1. Install the required dependencies:
   ```bash
   pip install numpy pandas scipy matplotlib seaborn jupyter
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

🤝 Contributing & Feedback

This is an open-source educational project. If you find any mathematical errors, want to optimize the code, or want to add a notebook for a specific chapter, feel free to open a Pull Request (PR) or submit an Issue!

👩‍💻 About the Author

Taghred Salah 
Computer Engineer & Data Scientist
I build data pipelines for complex scientific datasets and create educational STEM content (Sarmady Sci). My goal is to make astrophysics accessible, visual, and computational.

*   [LinkedIn](https://www.linkedin.com/in/taghredsalah199)
*   [Kaggle](https://www.kaggle.com/taghredsalah199)
*   

---
*Disclaimer: This repository is for educational purposes and is not affiliated with the authors or publishers of "An Introduction to Modern Astrophysics".*
---

Disclaimer: This repository is for educational purposes and is not affiliated with the authors or publishers of "An Introduction to Modern Astrophysics".

```