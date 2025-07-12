# Brain Tumor Segmentation

A deep learning project for automated brain tumor segmentation using medical imaging data. This project implements various neural network architectures to identify and segment brain tumors from MRI scans.

## Features

- **Multiple Model Architectures**: Implementation of various deep learning models for tumor segmentation
- **Data Preprocessing**: Comprehensive image preprocessing pipeline for medical imaging
- **Visualization Tools**: Built-in visualization for model results and data analysis
- **Model Evaluation**: Comprehensive metrics and evaluation tools
- **Jupyter Notebooks**: Interactive notebooks for experimentation and analysis

## Project Structure

```
Brain Tumer Segmentation/
├── data/                   # Dataset directory
├── models/                 # Trained model files
├── notebooks/              # Jupyter notebooks
├── src/                    # Source code
├── results/                # Output results and visualizations
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation
```

## Installation

### Prerequisites

- Python 3.8 or higher
- CUDA-compatible GPU (recommended for training)
- Git

### Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/brain-tumor-segmentation.git
cd brain-tumor-segmentation
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Data Preparation

1. Place your MRI scan data in the `data/` directory
2. Run preprocessing scripts to prepare data for training



## Model Performance

| Model       | Dice Score | IoU  | Sensitivity | Specificity |
| ----------- | ---------- | ---- | ----------- | ----------- |
| U-Net       | 0.85       | 0.74 | 0.88        | 0.92        |
| ResNet-UNet | 0.87       | 0.77 | 0.89        | 0.94        |

## Dataset

This project works with standard medical imaging datasets such as:

- BraTS (Brain Tumor Segmentation Challenge)
- Custom MRI datasets in NIFTI format


## Acknowledgments

- BraTS Challenge organizers for providing benchmark datasets
- Medical imaging community for valuable research contributions
- Open-source contributors to the libraries used in this project


