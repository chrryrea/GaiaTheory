# Gaia Hypothesis & Global Warming: Visualizing Earth's Feedback Loops

## Essential Question  
**"Are Earth's self-regulating systems being overwhelmed by contemporary global warming, and what does this mean for planetary stability as well as our futures?"**

## Data Sources  
### 1. **Global Temperature Anomalies**  
   - **Source:** [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/)  
   - **Format:** CSV  
   - **Description:** Monthly/Annual temperature anomalies (1880–present).  
   - **Usage:** Baseline for comparing Gaia-predicted stability against observed warming trends.  

### 2. **CO₂ Emissions & Feedback Data**  
   - **Source:** [Climate TRACE](https://climatetrace.org/data)  
   - **Format:** CSV  
   - **Description:** Sector-specific emissions data (2015–2024).  
   - **Usage:** Track human-driven emissions vs. natural carbon sink efficiency.  

### 3. **MIT Climate Projections**  
   - **Source:** [MIT Integrated Global System Model](https://globalchange.mit.edu/data)  
   - **Format:** CSV (Gridded 0.5° resolution)  
   - **Description:** Projected temperature/CO₂ scenarios (2021–2100).  
   - **Usage:** Simulate Gaia's future regulatory capacity under different emissions pathways.  

### 4. **Gaia Hypothesis Critiques**  
   - **Source:** [Springer: Critiques of Gaia](https://link.springer.com/article/10.1023/A:1023494111532)  
   - **Format:** PDF (Key excerpts in `/data` folder)  
   - **Usage:** Contextualize data anomalies (e.g., methane spikes contradicting Gaia stability).  

## Data Files  
- **Raw Data Links:**  
  - [`NASA_GISTEMP.csv`](https://data.giss.nasa.gov/gistemp/)  
  - [`Climate_TRACE_Global.csv`](https://climatetrace.org/data)  
- **Processed Data Samples:**  
  - `processed/gaia_feedback_2023.csv` (Cleaned merged dataset for visualization)  

## Visualization Approaches  
### 1. **Interactive 3D Globe**  
   - **Tech Stack:** React + Three.js  
   - **Features:**  
     - Layer toggles for CO₂ emissions, deforestation, and ocean heat.  
     - Timeline slider (1950–2100) to visualize "Gaia stress" over time.  
   - **Wireframe:**  
     ![Globe Wireframe](wireframes/globe_sketch.png) *(Placeholder for draft Excel/Sheets visualization)*  

### 2. **Feedback Loop Dashboard**  
   - **Tech Stack:** React + D3.js  
   - **Visualizations:**  
     - **Line Chart:** Temperature vs. CO₂ (1850–2024) with Gaia stability thresholds.  
     - **Scatter Plot:** Ocean pH vs. Industrial Emissions (highlight tipping points).  
   - **Wireframe:**  
     ![Dashboard Wireframe](wireframes/dashboard_sketch.png)  

### 3. **Gaia Stress Test Simulator**  
   - **Tech Stack:** React + Recharts  
   - **Features:**  
     - Sliders to adjust variables (e.g., "Deforestation Rate", "Fossil Fuel Use").  
     - Real-time projections of biodiversity loss and temperature rise.  
   - **Sample Simulation Output:**  
     ```bash
     Deforestation: 2%/year → Projected Amazon Collapse: 2045 (±3 years)
     ```  
