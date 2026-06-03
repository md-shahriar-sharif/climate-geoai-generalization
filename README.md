# Geographic Generalization as a First-Class Problem in Climate GeoAI

## A Cross-City Benchmark and Failure-Decomposition Framework for Urban Heat

This repository contains code, workflows, and experiments for evaluating geographic generalization in Climate GeoAI.

### Research Goal

Can geospatial foundation models improve transferability of urban heat prediction across cities?

### Main Components

- Census and socio-environmental data
- Google Earth Engine feature extraction
- Prithvi-EO-2.0 embeddings
- Random Forest and XGBoost baselines
- Geographic transfer evaluation
- Failure decomposition analysis
- Spatial explainability

### Compute Strategy

#### Laptop (CPU)

- Data processing
- Feature engineering
- Random Forest
- XGBoost
- SHAP / GeoShapley
- MGWR
- Visualization

#### Cloud GPU (Colab/Kaggle)

- Prithvi embedding extraction only

Embeddings are extracted once and reused for all experiments.
