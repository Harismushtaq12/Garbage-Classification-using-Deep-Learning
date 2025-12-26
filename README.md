# Garbage Classification using Deep Learning

This repository implements an **image classification pipeline for garbage / waste classification** using deep learning.
The goal is to automatically classify waste images into predefined categories to support **recycling**, **waste sorting**, and **sustainability** workflows.

The full implementation is provided in a Jupyter Notebook for reproducibility.

---

## Features
- Multi-class image classification for waste categories
- Deep learning training workflow (data loading, preprocessing, training, evaluation)
- Training curves (accuracy/loss) visualization
- Notebook-based, easy-to-run and extend

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV (optional)
- Scikit-learn (optional)
- Jupyter Notebook

---

## Project Structure

```
garbage-classification-image-classification/
├─ notebooks/
│  └─ Garbage_Classification.ipynb
├─ README.md
├─ requirements.txt
├─ LICENSE
├─ .gitignore
└─ docs/
   └─ NOTES.md
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook:

```bash
jupyter notebook notebooks/Garbage_Classification.ipynb
```

---

## Notes
- Ensure your dataset folder structure matches the notebook expectations (class folders).
- For best results, use a balanced dataset and consistent image sizes.
- Consider adding data augmentation or transfer learning for improved performance.

---

## License
MIT License
