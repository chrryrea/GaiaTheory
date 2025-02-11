# Gaia Hypothesis & Global Warming: Visualizing Earth's Feedback Loops
## Essential Question  
**"Are Earth's self-regulating systems being overwhelmed by contemporary global warming, and what does this mean for planetary stability as well as our futures?"**

## Data Sources  
### 1. **Global Temperature Anomalies**  
   - **Source:** [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/)  
   - **Format:** CSV  
   - **Description:** Monthly/Annual temperature anomalies (1880–present).  
   - **Usage:** Baseline for comparing predicted stability against warming trends.  

### 2. **CO₂ Emissions & Feedback Data**  
   - **Source:** [Climate TRACE](https://climatetrace.org/data)  
   - **Format:** CSV  
   - **Description:** Sector-specific emissions data (2015–2024).  
   - **Usage:** Track human-driven emissions vs. natural carbon sink efficiency.  

### 3. **MIT Climate Projections**  
   - **Source:** [MIT Integrated Global System Model](https://globalchange.mit.edu)  
   - **Format:** CSV  
   - **Description:** Projected temperature/CO₂ scenarios (2021–2100).  
   - **Usage:** Simulate Gaia's future regulatory capacity under different emissions pathways.  

### 4. **Gaia Hypothesis Critiques**  
   - **Source:** [Springer: Critiques of Gaia](https://link.springer.com/article/10.1023/A:1023494111532)  
   - **Format:** PDF 
   - **Usage:** Contextualize data anomalies

## Data Files  
- **Raw Data Links:**  
  - [`NASA_GISTEMP.csv`](https://data.giss.nasa.gov/gistemp/)  
  - [`Climate_TRACE_Global.csv`](https://climatetrace.org/data)  

## Visualization Approaches  
### 1. **Interactive 3D Globe**  
   - **Tech Stack:** React + Three.js  
   - **Features:**  
     - Layer toggles for CO₂ emissions, deforestation, and ocean heat.  
     - Timeline slider (1950–2100) to visualize "Gaia stress" over time.  
   - **Wireframe:**  
     ![Globe Wireframe](wireframes/globe_sketch.png) *(Placeholder)*  

### 2. **Gaia Stress Test Simulator (Possible)**   
   - **Tech Stack:** React + Recharts  
   - **Features:**  
     - Sliders to adjust variables (e.g., "Deforestation Rate", "Fossil Fuel Use").  
     - Real-time projections of biodiversity loss and temperature rise.  
   - **Sample Simulation Output:**  
     ```bash
     Deforestation: 2%/year → Projected Amazon Collapse: 2045 (±3 years)
     ```  

gaiatheory-vis/
├── data/
│ ├── raw/ # Links to external datasets
│ └── processed/ # Cleaned data
├── src/
│ ├── components/ # React components
│ ├── utils/ # Data parsing scripts
│ └── App.js # Main dashboard
├── public/
│ └── wireframes/
├── LICENSE
└── package.json
