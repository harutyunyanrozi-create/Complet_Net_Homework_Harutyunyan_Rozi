# NET4103 - Network Science Homework
**Student:** Rozi  
**Date:** Mai 2026

## Project Structure
- `Q2_analysis.ipynb` - Social network analysis (degree dist, clustering)
- `Q3_assortativity.ipynb` - Assortativity analysis across 100 networks
- `Q4_link_prediction.ipynb` - Link prediction algorithms
- `Q5_label_propagation.ipynb` - GCN-based label propagation
- `Q6_communities.ipynb` - Community detection analysis

## Dataset
Facebook100 dataset (September 2005 snapshot)
- 100 US university networks
- Node attributes: student/faculty, major, dorm, gender, year

## How to Run
```bash
conda create -n net4103 python=3.9
conda activate net4103
pip install -r requirements.txt
jupyter notebook
```

## Results
See `results/` folder for all figures and tables.
