# 🧠 Breast Cancer Classification (UCI Dataset)

This project uses machine learning and deep learning models to classify breast cancer diagnoses using the UCI Breast Cancer Wisconsin Diagnostic dataset. The entire workflow from data exploration to model evaluation is implemented in a Jupyter Notebook. Achieved an accuracy of 94.76% for this classification model.

## 📁 File

- `CancerClassificationModel.ipynb`: Complete notebook including data preprocessing, visualizations, model training, and evaluation.

## 📊 Dataset

- **Source**: [UCI Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Samples**: 569  
- **Features**: 30 numerical features (mean, standard error, worst)  
- **Target**: Diagnosis (`M` = malignant, `B` = benign)

## 🛠️ Libraries Used

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `tensorflow`  
- `keras`  

## 🚀 Workflow

1. Load and inspect the dataset  
2. Preprocess and normalize feature values  
3. Visualize distributions and feature correlations  
4. Train using a multi-layer preceptron neural network
5. Validate the ML model on the test data
6. Evaluate using accuracy and classification report


## 📈 Results
- Accuracy: ~94.74% accuracy

## 🧪 Run the Notebook

To run this project locally:

1. **Clone the repo**:
    ```bash
    git clone https://github.com/yourusername/cancer-classification.git
    cd cancer-classification
    ```

2. **(Optional) Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Launch Jupyter**:
    ```bash
    jupyter notebook
    ```

Then open `CancerClassificationModel.ipynb`.
