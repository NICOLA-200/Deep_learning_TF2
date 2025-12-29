[![GitHub issues](https://img.shields.io/github/issues/sniper0110/IntroductionToTensorflow2)](https://github.com/sniper0110/IntroductionToTensorflow2/issues)

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/tensorflow)

# Introduction to Tensorflow 2
Code related to the course "Introduction to Tensorflow for computer vision"


## 🚀 Features

- TensorFlow 2 / Keras-based models  
- Clean separation of:
  - Models
  - Utilities
  - Training & inference
- Image classification examples
- Easy to extend for new datasets and models

---

## 🧠 Examples Included

### 1. MNIST Classification
Train and evaluate a neural network to recognize handwritten digits (0–9).

```bash
python mnist_example.py
```

### Create environment
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
```

### install dependencies
```bash
pip install -r requirements.txt
```

### Image classification example for recognizing street signs.

```bash
python street_signs_example.py
```

### Use the predictor module to load a trained model and run inference:

```bash
python my_predictor.py