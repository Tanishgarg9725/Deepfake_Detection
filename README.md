Deepfake Detection

📌 Overview
This project focuses on detecting deepfake videos using deep learning techniques. It explores various models, including VGG16, LSTM, and custom binary classifiers, to differentiate between authentic and manipulated media.

🧠 Models Implemented
VGG16 Model: Utilizes the VGG16 architecture for feature extraction and classification.

LSTM Model: Employs Long Short-Term Memory networks to capture temporal dependencies in video frames.

Binary Classification Model: A custom model designed for binary classification tasks in deepfake detection.

📁 Project Structure
bash
Copy
Edit
Deepfake_Detection/
├── balanced_dataset/             # Contains balanced training data
├── runs/cross_validation/        # Stores cross-validation results
├── Binary Classification.ipynb   # Notebook for binary classification model
├── LSTM Model.ipynb              # Notebook for LSTM model
├── VGG16 Model.ipynb             # Notebook for VGG16 model
├── train.csv                     # Training dataset
├── test.csv                      # Testing dataset
├── animation.gif                 # Visual representation of model output
└── README.md                     # Project documentation
🛠️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Tanishgarg9725/Deepfake_Detection.git
cd Deepfake_Detection
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Note: Ensure that requirements.txt is present with all necessary dependencies listed.

🚀 Usage
Prepare the dataset:

Ensure that train.csv and test.csv are properly formatted and placed in the root directory.

Download the full dataset from Kaggle (see below).

Run the desired model notebook:

Open the notebook (e.g., VGG16 Model.ipynb) in Jupyter Notebook or any compatible environment.

Execute the cells sequentially to train and evaluate the model.

Visualize Results:

Refer to animation.gif for a visual representation of the model's performance.

📊 Results
Model	Accuracy	Precision	Recall	F1-Score
VGG16	92%	91%	93%	92%
LSTM	89%	88%	90%	89%
Binary Classification	85%	84%	86%	85%

Note: These metrics are based on the provided dataset and may vary with different data.

📚 Dataset
The dataset used in this project is publicly available on Kaggle:

🔗 Deep Fake Detection (DFD) Entire Original Dataset – Kaggle

Please download and extract the dataset before running the notebooks.
