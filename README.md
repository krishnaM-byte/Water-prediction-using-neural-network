# Water-prediction-using-neural-network
This project aims to predict the potability (drinkability) of water using a neural network-based classification model. It leverages various physicochemical properties of water (such as pH, hardness, solids, chloramines, sulfate, etc.) to determine whether a given water sample is safe for human consumption.

✅ Key Features:
Uses a clean and labeled dataset (e.g., Kaggle Water Quality dataset)
Implements a deep learning model using libraries like TensorFlow/Keras or PyTorch
Evaluates the model using metrics like accuracy, precision, recall, and F1-score
Includes data preprocessing, normalization, and train-test split
Visualizes training performance using graphs
Fully reproducible code in a Jupyter Notebook

📁 Project Structure:

water-quality-nn/
│
├── data/                   # Dataset CSV
├── notebooks/              # Jupyter notebook with training & evaluation
├── models/                 # Saved model (optional)
├── README.md               # Project overview
└── requirements.txt        # List of dependencies

📊 Dataset:
Source: Kaggle - Water Quality Dataset
Contains 9 features and 1 binary label:
Features: pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity
Label: Potability (1 = drinkable, 0 = not drinkable)

🧠 Model Architecture:
Input layer: 9 neurons (one for each feature)
Hidden layers: 2-3 dense layers with ReLU activation
Output layer: 1 neuron with sigmoid activation (binary classification)

🚀 Getting Started:
1.Clone the repo
2. Install dependencies:
pip install -r requirements.txt
3.Run the notebook:
jupyter notebook notebooks/water_quality_nn.ipynb







