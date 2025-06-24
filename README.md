# Seismic Point Cloud Explorer

This repository provides an interactive Jupyter Notebook for visualizing 3D seismic data as a point cloud using Plotly. You can adjust the cropping range, amplitude threshold, and sampling rate, and view the data in a fully interactive 3D scatter plot.

## 📦 Dataset

To use this notebook, download the seismic dataset as described in the excellent work:

➡️ **[Facies Classification Benchmark by yalaudah](https://github.com/yalaudah/facies_classification_benchmark)**

Please follow the instructions in that repo to obtain the `train_seismic.npy` and `train_labels.npy` files.

After downloading, place the files in the same directory as the notebook, or adjust the path accordingly in the notebook.


## 🛠️ Environment Setup

1. Clone this repository:
```bash
git clone https://github.com/JackmanYuan/seismic-pointcloud-viewer.git
cd seismic-pointcloud-viewer
```

2.	It’s recommended to use a clean Python environment (e.g., via conda or venv).
3.	Install required packages:
```bash
pip install -r requirements.txt
```


## 📘 How to Use
1.	Launch the F3_Netherlands_dataset_visualization .ipynb file:
2.	Adjust the following parameters via the sidebar sliders:
- Threshold: Minimum amplitude to visualize
- Inline / Crossline / Depth: Define the sub-volume to crop
- Sample Rate: Control how many points to skip to speed up rendering
3.  Enjoy rotating, zooming, and exploring the 3D seismic volume interactively!


## 📷 Preview
![visualize_seismic](https://github.com/user-attachments/assets/6f8d47b8-c3d0-45e4-bb6a-cad409a222bd)

## 🧠 Credits
- Data: Facies Classification Benchmark

## 📄 License

This project is licensed under the MIT License
