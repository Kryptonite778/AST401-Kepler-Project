# AST401 Project – Kepler Planets Mass, Radius, and Density

## 🔭 Overview
This project analyzes **Kepler-discovered exoplanets** using data from the 
[NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).  
We focus on comparing their **mass, radius, and density** to Earth and Saturn.

## 📊 Methodology
1. **Dataset Fetching**  
   - Data was retrieved via the NASA Exoplanet Archive TAP service.  
   - Selected parameters: planet name, mass (Earth masses), radius (Earth radii).  

2. **Density Calculation**  
   - Density calculated relative to Earth’s density (5.51 g/cm³):  
     \[
     \rho = \frac{M}{R^3} \times 5.51
     \]  
     where \(M\) = mass in Earth units, \(R\) = radius in Earth units.  

3. **Visualization**  
   - A scatter plot of **Mass vs Radius** was generated.  
   - Planets are color-coded by density, with Earth and Saturn as reference points.  

4. **Planet Selection Criteria**  
   - **Planet 1:** More dense than Earth  
   - **Planet 2:** Density between Earth and Saturn  
   - **Planet 3:** Less dense than Saturn  

## 🌍 Selected Planets
- **Planet more dense than Earth:** *Kepler-10b* (≈ 12.4 g/cm³)  
- **Planet between Earth & Saturn:** *Kepler-22b* (≈ 2.8 g/cm³)  
- **Planet less dense than Saturn:** *Kepler-51b* (≈ 0.03 g/cm³)  

## 📈 Results
- Kepler-10b is a dense rocky planet, significantly denser than Earth.  
- Kepler-22b has an intermediate density, suggesting a possible water-rich or gas-rich composition.  
- Kepler-51b is an extremely low-density "cotton candy" planet, less dense than Saturn.  

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Numpy  

## 🚀 How to Run
1. Open the notebook in **Google Colab** or Jupyter Notebook.  
2. Run all cells to fetch the data, calculate density, and generate plots.  
3. Modify selection criteria as needed to explore other planets.  

---
**Author:** [Your Name]  
Course: AST401
