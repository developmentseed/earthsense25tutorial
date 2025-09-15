# GeoAI in the Cloud: From Data Formats to Foundation Models

Welcome to the EarthSense 2025 EOFM tutorial 🥳! This Jupyter book 📖 contains notebooks on
how to apply 🧱 Foundation Models to 🛰️ Earth Observation data.

## 📚 Overview of tutorials

1. Introduction to Cloud Native Data Formats
2. Introduction to EO Foundation Models
3. Applying Foundation Models to Segmentation downstream task

Each tutorial is rendered on this website for easy viewing 👀, but some of them are
Jupyter notebooks designed to be ran interactively 💫. See the instructions below on how
you can start running the tutorials in no time! 🚀

## 🌠 Setting up your environment

To run these notebooks in an interactive Jupyter session online, 🖱️ click on the button
below to launch on
[Google Colaboratory](https://colab.google).

Notebooks
- **Exploring Cloud Native Geospatial Data Formats with ERA5 Reanalysis Data** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/developmentseed/earthsense25tutorial/blob/main/01_stac_and_zarr.ipynb)
- **Fine-tuning Clay Foundation Model for Land Cover Segmentation** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/developmentseed/earthsense25tutorial/blob/main/03_EOFM_finetuning.ipynb)

### 💻 Creating a local environment for running tutorials

If you prefer to run the tutorials locally, follow these simple steps:

1. Ensure you have [`uv`](https://docs.astral.sh/uv/getting-started/installation) installed.

2. Clone the repository and set up the environment:

   ```bash
   git clone https://github.com/developmentseed/earthsense25tutorial.git
   cd earthsense25tutorial
   uv sync
   ```

3. Launch Jupyter Lab:

   ```bash
   uv run jupyter lab
   ```

You're now ready to run the tutorials! 🎉


```{admonition} Acknowledgements
The contents of the first two tutorial pages are derived from a draft chapter on
Foundation Models that will become a part of
[the SERVIR Applied Deep Learning Book](https://servir.github.io/SERVIR-Applied-Deep-Learning-Book).
We would like to thank [SERVIR](https://servirglobal.net) for their generous permission
to re-purpose the contents of the book chapter for this EarthSense 2025 tutorial.
```
