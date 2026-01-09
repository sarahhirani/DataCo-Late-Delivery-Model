# 📦 Supply Chain Late Delivery Prediction Model (97% Accuracy)

This project applies machine learning to the DataCo Supply Chain dataset to predict late delivery risk using operational data.  
The model uses **RandomForestClassifier** and achieves:

- **97% accuracy**  
- **ROC-AUC: 0.97**  
- **High precision & recall balance**


## 🚀 Project Goal

To proactively identify which orders are at risk of late delivery based on operational variables such as:

- scheduled shipping days  
- actual shipping days  
- shipping mode  
- order quantity  
- product price  
- shipping lead time  


## 🛠 Tools & Techniques

- Python  
- Pandas  
- Scikit-Learn  
- Matplotlib / Seaborn  
- Random Forest Classification  
- Feature Engineering  
- Model Evaluation  


## 📊 Key Visuals

**Feature Importance**  
`visuals/feature_importance.png`

**Confusion Matrix**  
`visuals/confusion_matrix.png`


## 📚 Notebook File

The complete training pipeline is located in:

notebooks/01_model_training.ipynb


## 💡 Insights

- Shipping mode is a major driver of late deliveries  
- Higher scheduled shipping days do not guarantee on-time performance  
- Certain product pricing patterns correlate with higher delay rates  
- Machine learning can reliably flag at-risk shipments  


## 📁 Structure

DataCo-Late-Delivery-Model/
│
├── visuals/
│ ├── confusion_matrix.png
│ └── feature_importance.png
│
├── notebooks/
│ └── 01_model_training.ipynb
│
└── README.md


## 👩‍💻 Author

**Sarah Hirani**  
Supply Chain Analytics & Operations

