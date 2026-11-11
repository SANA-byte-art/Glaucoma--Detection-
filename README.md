# Glaucoma Detection Using Deep Learning

## Project Overview

This project explores the use of Deep Learning and Convolutional Neural Networks (CNN) to classify retinal fundus images into two categories: **Glaucomatous** and **Healthy**.

A Streamlit-based web application was developed to allow users to upload an eye fundus image and receive a model-generated classification.

## Objectives

- Explore medical image classification using Deep Learning.
- Train a CNN model to distinguish between healthy and glaucomatous retinal images.
- Preprocess fundus images for model training and prediction.
- Develop a simple web interface using Streamlit.

## Technologies Used

- **Programming Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Web Framework:** Streamlit
- **Image Processing:** Pillow (PIL)
- **Numerical Computing:** NumPy
- **Development Tools:** Jupyter Notebook, VS Code

## Project Structure

```text
Glaucoma-Detection/
│
├── Glaucoma/
│   └── Glaucoma/
│       ├── glaucoma_app.py
│       ├── train.py
│       ├── optical.ipynb
│       ├── index.html
│       ├── requirements.txt
│       └── GlaucomaOutput.docx
│
├── README.md
├── .gitignore
└── Running Procedure..txt
```

## How It Works

1. Retinal fundus images are collected and organised into two categories: Glaucomatous and Healthy.
2. Images are processed and prepared for training.
3. A Convolutional Neural Network (CNN) is trained using the image dataset.
4. The trained model is used to classify uploaded fundus images.
5. A Streamlit application provides a simple interface for image upload and prediction.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SANA-byte-art/Glaucoma--Detection-.git
```

### 2. Navigate to the Project Directory

```bash
cd Glaucoma--Detection-/Glaucoma/Glaucoma
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add the Trained Model

The trained model file (`my_model2.h5`) and image datasets are not included in this GitHub repository.

The application requires `my_model2.h5` in the project directory to run.

### 5. Run the Application

```bash
streamlit run glaucoma_app.py
```

## Repository Contents

This repository focuses on the project's source code, training scripts, Jupyter notebook and documentation.

The trained model and original image datasets are excluded to keep the repository lightweight.

## Future Improvements

- Improve model performance using larger and more diverse datasets.
- Evaluate classification performance using appropriate metrics.
- Improve the web application's user interface.
- Explore deployment options for the application.

## Disclaimer

This project is developed for educational and research purposes only. Its predictions are not a substitute for professional medical advice, diagnosis or treatment. Always consult a qualified ophthalmologist for medical evaluation.

## Author

**SANA-byte-art**

GitHub: https://github.com/SANA-byte-art