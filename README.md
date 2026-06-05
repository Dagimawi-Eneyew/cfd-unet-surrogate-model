<a href="https://colab.research.google.com/github/Dagimawi-Eneyew/CFD-SurrogateUsingUNET/blob/main/">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# CFD U-Net Surrogate Model

A deep learning surrogate that predicts 2-D wind velocity fields from building geometry, replacing computationally expensive CFD simulations.

## Notebooks

**`data-preprocessing-pipeline.ipynb`** — Transforms raw building geometry images and CFD velocity-field outputs into physics-aware input tensors ready for model training.

**`unet-model-training.ipynb`** — Trains and evaluates a U-Net on the preprocessed dataset, producing a model that maps geometry and wind speed inputs to predicted velocity fields.

## Dataset

296 cases covering 9 inlet wind speeds (2–10 m/s). The dataset is publicly available on Google Drive; setup instructions are included in the preprocessing notebook.

## Reference

Vandewiel, Eneyew, Awol, Capretz & Bitsuamlak (2025). *Approximating CFD simulations of natural ventilation: A deep surrogate model with spatial attention mechanism.* Journal of Building Engineering, 105, 112425.
