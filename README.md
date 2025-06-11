# Cat Image Classification with Fastai

This repository contains a deep learning model built using the **Fastai** library to classify images of cats into distinct categories. The model leverages Fastai's high-level API and transfer learning techniques to achieve accurate classification with minimal code.
##  Project Overview

- **Framework**: Fastai (built on PyTorch)
- **Objective**: Classify different breeds/types of cats based on image data
- **Workflow**: Image loading → Preprocessing → Training → Evaluation → Inference
- **Notebook**: [`fastAI.ipynb`](./fastAI.ipynb)

---

##  Files

- `fastAI.ipynb`: Jupyter notebook containing the full workflow.
- `models/export.pkl`: (optional) Exported trained model for inference.
- `data/cats/`: Folder containing cat images organized into subfolders by category.

---

##  Setup Instructions

### 1. Clone this repository

```bash
git clone https://github.com/yourusername/cat-classifier-fastai.git
cd cat-classifier-fastai
