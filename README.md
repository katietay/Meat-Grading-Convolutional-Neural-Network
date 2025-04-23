# Image Segmentation and Classification with PyTorch and DeepLab

This project was developed for the **USDA/CSU 2024 Hackathon**, where the goal was to design a machine learning system capable of grading meat based on image data. It leverages PyTorch and a custom convolutional neural network, along with DeepLab, to classify visual features relevant to meat quality assessment.

The repository includes both an interactive Jupyter Notebook and a standalone Python script to support model development, experimentation, and evaluation.

---

## Overview

- `DeepLab.ipynb`: A notebook for exploring image data, configuring models, and analyzing results.
- `Neural-Network.py`: A Python script that runs the full training and validation pipeline.
- Stratified K-Fold cross-validation for robust performance metrics.
- Supports custom datasets with dynamic transformations and label mapping.
- Outputs results in CSV format for easy post-processing and analysis.

---

## Installation

### Requirements

- Python 3.7 or later  
- Jupyter Notebook or Google Colab  
- Python libraries:
  - `torch`
  - `torchvision`
  - `pandas`
  - `openpyxl`

### Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/image-segmentation-pytorch.git
cd image-segmentation-pytorch
pip install torch torchvision pandas openpyxl
```

## Usage

### Jupyter Notebook

To explore and train the model interactively:

1. Open `DeepLab.ipynb` in Jupyter Notebook or Google Colab.  
2. Follow the cells to:
   - Load and preprocess image data  
   - Train the CNN model  
   - Evaluate results using metrics like accuracy and loss

### Python Script

To run the automated workflow from the command line:

```bash
python Neural-Network.py
```
This script handles the entire process: loading data, training, validating, and exporting results.

## Project Structure

image-segmentation-pytorch/
├── DeepLab.ipynb          # Interactive notebook for modeling and evaluation
├── Neural-Network.py      # Script for full model training workflow
├── LICENSE                # License file
├── README.md              # Project documentation
└── .ipynb_checkpoints/    # Auto-generated notebook backup files

## Contributing
Contributions are welcome. To contribute:
1. Fork the repository  
2. Create a new branch:  
   `git checkout -b feature/your-feature-name`  
3. Commit your changes:  
   `git commit -m "Add feature"`  
4. Push to your branch:  
   `git push origin feature/your-feature-name`  
5. Open a pull request

## License
This project is licensed under the [MIT License](LICENSE). You may use, modify, and distribute it under the terms of this license.

## Contact
For questions, collaboration, or feedback:
- **Name**: Katie Taylor  
- **Email**: katietaylorcruz@gmail.com  
- **GitHub**: [https://github.com/katietay](https://github.com/katietay)
