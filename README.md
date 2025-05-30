# Deepfake Detection

## 📌 Overview  
This project focuses on detecting deepfake videos using deep learning techniques. It explores various models, including **VGG16**, **LSTM**, and custom **binary classifiers**, to differentiate between authentic and manipulated media.

---

## 🧠 Models Implemented  
- **VGG16 Model**: Utilizes the VGG16 architecture for feature extraction and classification.  
- **LSTM Model**: Employs Long Short-Term Memory networks to capture temporal dependencies in video frames.  
- **Binary Classification Model**: A custom model designed for binary classification tasks in deepfake detection.

---

## 🚀 Usage

**Prepare the dataset:**
Ensure that train.csv and test.csv are properly formatted and placed in the root directory.
Download the full dataset from Kaggle (see below).

**Run the desired model notebook:**
Open the notebook (e.g., VGG16 Model.ipynb) in Jupyter Notebook or any compatible environment.
Execute the cells sequentially to train and evaluate the model.

**Visualize results:**
Refer to animation.gif for a visual representation of the model's performance.

---

## 📊 Results

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| **VGG16**              | 92%      | 91%       | 93%    | 92%      |
| **LSTM**               | 89%      | 88%       | 90%    | 89%      |
| **Binary Classification** | 85%  | 84%       | 86%    | 85%      |
