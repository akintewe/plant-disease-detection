# FarmGuard AI - Plant Disease Detection

Deep learning model to detect plant diseases from leaf images using CNN.

## Features
- Classifies common plant diseases (e.g., blight, rust, etc.)
- Built with TensorFlow/Keras (or PyTorch)
- Trained on PlantVillage dataset
- Accuracy: [add your number, e.g., 95% on test set]

## How to Use
1. Open `training.ipynb` in Jupyter/Colab
2. Run cells to load model
3. Use prediction function on your leaf image

Example prediction code:
```python
from tensorflow.keras.models import load_model
model = load_model('models/my_model.h5')
