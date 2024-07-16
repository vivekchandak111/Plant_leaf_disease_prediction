# Plant Leaf Disease Prediction Using Deep Learning

## Introduction
This project focuses on the classification of plant diseases using a Convolutional Neural Network (CNN) implemented with TensorFlow and Keras. The goal is to accurately identify whether a plant leaf is healthy or affected by diseases like powdery mildew or rust based on images.

## Project Structure
```
├── Dataset
│ ├── Train
│ │ ├── Healthy
│ │ ├── Powdery
│ │ └── Rust
│ ├── Test
│ │ ├── Healthy
│ │ ├── Powdery
│ │ └── Rust
│ └── Validation
│ ├── Healthy
│ ├── Powdery
│ └── Rust
├── static
│ ├── css
│ │ ├── bootstrap.min.css
│ │ └── test.css
│ ├── js
│ ├── bootstrap.min.js
│ ├── jquery.min.js
│ └── newjs.js
├── templates
│ ├── index.html
│ └── import.html
├── app.py
├── model.h5
└── README.md
```

Dataset Link: [https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset)
## Usage

**Web Interface:**

1. **Upload an Image:** Locate the file upload button on the web interface and select an image of a plant leaf you want to analyze.
2. **Predict the Disease:** Click the "Predict!" button to activate the deep learning model. The predicted disease (healthy or specific disease type) will be displayed.

## Additional Notes

- The accuracy of the disease classification depends heavily on the quality and size of the training dataset.
- This project is intended for educational purposes and might not be suitable for professional agricultural applications.

