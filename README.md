# Brain Connectome Analysis  

This repository contains code and analysis for studying the human brain's structural connectome using network science techniques. The project investigates graph properties, community detection, signal propagation, and the impact of simulated interventions like transcranial magnetic stimulation (TMS).  

---

## Table of Contents  
1. **Data**  
   - Preprocessed brain connectome data (at multiple resolutions).  
   - Node attributes (positions, regions, functions).  

2. **Analysis**  
   - Graph metrics (clustering, path lengths, centrality).  
   - Community detection algorithms (Louvain, Leiden, spectral clustering).  
   - TMS simulation models (heat diffusion, random walks).  

3. **Visualizations**  
   - 3D brain connectome plots.  
   - Community structure visualizations.  
   - Signal propagation heatmaps.  

4. **Methods**  
   - Parameter optimization for clustering algorithms.  
   - Statistical comparisons of community detection results.  

---

## Key Features  
- **Network Analysis:**  
  - Calculation of global and local graph properties (clustering, modularity, assortativity).  
  - Identification of critical hub nodes using centrality measures.  

- **Community Detection:**  
  - Comparison of 10+ algorithms (Louvain, Leiden, MCL, etc.).  
  - Validation against anatomical brain regions.  

- **TMS Simulation:**  
  - Edge weighting based on spatial distances.  
  - Propagation models for therapeutic stimulation effects.  

---

## Dependencies  
```bash  
networkx  
matplotlib  
numpy  
scipy  
plotly  
pandas  
powerlaw  
karateclub  
cdlib  
```  

---

## Getting Started  
1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/YoloPopo/Brain-Connectome-Analysis.git  
   ```  

2. **Install dependencies:**  
   ```bash  
   pip install networkx matplotlib numpy scipy plotly pandas powerlaw karateclub cdlib
   ```  

## Contributing  
Contributions are welcome! Open an issue for:  
- Bug reports.  
- Feature requests.  
- Dataset improvements.  

---

## License  
MIT License  
Copyright (c) 2023 [Yolo Popo]  

--- 

Let me know if you'd like to expand any section!
