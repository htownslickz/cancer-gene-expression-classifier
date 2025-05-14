# Cancer Type Classification from Gene Expression using Deep Learning

This project uses RNA-seq gene expression data to train a deep neural network to classify different cancer types.

## 🧬 Dataset
Data from The Cancer Genome Atlas (TCGA) via [UCSC Xena](https://xenabrowser.net/datapages/).

## 🧠 Model
A multi-layer perceptron (MLP) implemented in PyTorch.

## 📈 Results
Achieved 92% accuracy across 5 cancer types. See confusion matrix in `/outputs/`.

## 📁 Project Structure
- `notebooks/`: Exploratory and training notebooks
- `src/`: Scripts for model training and evaluation
- `data/`: Data preprocessing scripts or download instructions

## 🚀 Getting Started
```bash
pip install -r requirements.txt
python src/train_model.py
# cancer-gene-expression-classifier
