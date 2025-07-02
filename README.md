# 3D-UMAP-Visualization

This repository contains a Jupyter notebook that demonstrates how to generate and visualize 3D UMAP projections from single-cell RNA-seq data using Python. The notebook uses the Scanpy framework and Matplotlib's 3D plotting features to produce high-quality 3D scatter plots, with customized color mappings and legends based on cell annotations.

## 📌 Key Features

- Generates 3D UMAP embeddings from `adata.obsm['X_umap']`
- Custom coloring based on categorical metadata (e.g., cell types, clusters)
- Interactive rotation support for static or animated visualization
- Optional export of figures

## 🧰 Requirements

This notebook was developed using the following Python packages:

- `scanpy`
- `matplotlib`
- `mpl_toolkits.mplot3d`
- `numpy`
- `pandas`

You can install the required dependencies using:

```bash
pip install scanpy matplotlib pandas
