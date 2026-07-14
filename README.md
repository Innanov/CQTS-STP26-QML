# CQTS Summer Training Program 2026: Introduction to Quantum Machine Learning

This repository contains two beginner-friendly Jupyter notebooks prepared for high school students in the **CQTS Summer Training Program 2026**.

The notebooks introduce quantum machine learning through small classification tasks using **PennyLane**, **scikit-learn**, **Matplotlib**, and **Pandas**. Students first learn how classical data can be encoded as quantum rotation angles, then move to amplitude encoding and compare several quantum circuit designs.

## Learning path

| Order | Notebook | Main focus | Level |
|---:|---|---|---|
| 1 | `01_Introduction_to_QML_Iris_Angle_Encoding.ipynb` | Iris flower classification, angle encoding, four-qubit circuit, hybrid QML model, loss, accuracy, and classification metrics | Beginner |
| 2 | `02_QML_Architecture_Exploration_Digits_Amplitude_Encoding.ipynb` | Handwritten-digit classification, amplitude encoding, PCA, qubit counts, circuit depth, PennyLane templates, validation, and model comparison | Beginner to intermediate |

## Notebook 1: Introduction to QML

**Title:** *Classifying Iris Flowers with Angle Encoding*

Students will:

- Explore the Iris dataset.
- Scale four flower measurements into quantum rotation angles.
- Encode one feature on each of four qubits.
- Draw and inspect a PennyLane circuit.
- Create quantum features from circuit measurements.
- Train a classical output layer.
- Read loss, accuracy, a confusion matrix, and a classification report.
- Test the model with their own flower measurements.

## Notebook 2: QML Architecture Exploration

**Title:** *Classifying Handwritten Digits with Amplitude Encoding*

Students will:

- Work with small grayscale images of digits 0, 1, 2, and 3.
- Learn how amplitude encoding stores a normalized vector in a quantum state.
- Use PCA to prepare 16, 32, or 64 input values.
- Compare circuits with 4, 5, and 6 qubits.
- Compare 1, 2, and 3 quantum layers.
- Compare `BasicEntanglerLayers` and `StronglyEntanglingLayers`.
- Use validation accuracy to select a circuit.
- Evaluate the selected model using loss, accuracy, a confusion matrix, and a classification report.

## Requirements

The notebooks install missing packages automatically. The main packages are:

- Python 3
- PennyLane
- scikit-learn
- NumPy
- Pandas
- Matplotlib

## How to run the notebooks

1. Open the first notebook in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the cells from top to bottom.
3. Read the explanation before running each code cell.
4. Complete the student activities at the end.
5. Continue with the second notebook after finishing the Iris lesson.

