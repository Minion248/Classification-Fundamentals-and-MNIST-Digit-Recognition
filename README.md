# **MNIST Digit Classification Project**

## **Project Overview**
This project implements a machine learning system for classifying handwritten digits (0-9) using the classic MNIST dataset. It includes:
- Data preprocessing and exploration
- Implementation of SGD and Random Forest classifiers
- Comprehensive model evaluation and error analysis
- Hyperparameter optimization
- Interactive Gradio web interface for real-time predictions

## **Key Features**
✔ **Two Classification Models**:  
   - SGD Classifier (linear SVM)  
   - Random Forest Classifier  

✔ **Performance Metrics**:  
   - 97.05% test accuracy (Random Forest)  
   - Detailed confusion matrix analysis  

✔ **Error Analysis**:  
   - Identified common misclassifications (e.g., 9→4)  
   - Implemented data augmentation improvements  

✔ **Interactive Demo**:  
   - Gradio web interface for live digit recognition  

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mnist-digit-classification.git
   cd mnist-digit-classification
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## **File Structure**
```
├── data/                    # MNIST dataset (auto-downloaded)
├── notebooks/
│   ├── 01_Data_Exploration.ipynb
│   ├── 02_Model_Training.ipynb
│   └── 03_Error_Analysis.ipynb
├── models/
│   ├── sgd_model.pkl        # Trained SGD classifier
│   └── rf_model.pkl         # Trained Random Forest
├── app.py                   # Gradio application
├── requirements.txt         # Python dependencies
└── README.md
```

## **Usage**
1. **Run Jupyter notebooks** to explore the analysis:
   ```bash
   jupyter notebook
   ```

2. **Launch the Gradio app**:
   ```bash
   python app.py
   ```
   Then open `http://localhost:7860` in your browser to test the classifier.

## **Results**
| Model | Accuracy | Training Time |
|-------|----------|---------------|
| SGD Classifier | 95.12% | ~30 sec |
| Random Forest | 97.05% | ~2 min |
 
 
