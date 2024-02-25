
# Custom Integrated Image-Tabular Model for Melanoma Classification

## Overview
This project presents a groundbreaking approach to melanoma classification, combining Convolutional Neural Networks (CNN) with a tabular model to analyze both image data and structured data (e.g., age, sex, skin color, and other biological factors). This custom integrated model leverages the strengths of both worlds to achieve higher accuracy and provides a more comprehensive analysis than traditional image-based models.

## Features
- **Custom Integrated Model**: Unique CNN + Tabular model architecture to consider both image features and patient metadata.
- **Comprehensive Data Analysis**: Utilizes a wide range of data points, including patient demographics and biological factors, alongside image data.
- **High Accuracy**: Designed to improve melanoma classification accuracy by considering multiple data dimensions.
- **FastAI Integration**: Built using FastAI's powerful libraries for both vision and tabular data, ensuring efficient training and prediction.

## Technology Stack
- Python
- OpenCV for image preprocessing
- NumPy for numerical computations
- Pandas for data manipulation
- Matplotlib for data visualization
- FastAI for deep learning
- `image_tabular` library for integrating image and tabular data in deep learning models

## Installation and Setup
Ensure you have Python 3.6+ installed on your system. Then, follow the steps below to set up your environment:

1. Clone the repository:
```bash
git clone https://github.com/bhavya1600/melanoma-classification-custom-image-tabular-model.git
cd melanoma-classification-custom-image-tabular-model
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
To run the model, navigate to the project directory and execute the Jupyter Notebook:
```bash
jupyter notebook Melanoma_Custom_Integrated_Image_Tabular_DenseNet161.ipynb
```

Follow the instructions within the notebook for detailed steps on data preprocessing, model training, and evaluation.

## Contributing
Contributions are welcome! If you have improvements or bug fixes, please open an issue or pull request.

## License
This project is released under the MIT License.

