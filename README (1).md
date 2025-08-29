# Decision Tree Classifier from Scratch  

## 📌 Overview  
This project implements a **Decision Tree Classifier** built completely from scratch using Python.  
The aim is to understand the internal working of decision trees, including splitting criteria, recursive tree building, and prediction.  

---

## 🚀 Features  
- Implementation of decision trees **without using scikit-learn's DecisionTreeClassifier**.  
- Custom implementation of splitting based on **Gini Index / Entropy**.  
- Recursive construction of tree nodes.  
- Prediction function for unseen samples.  
- Easy to extend and visualize.  

---

## 📂 Project Structure  
```
├── DecisionTreeScratch.ipynb   # Jupyter Notebook with code and explanations
├── README.md                    # Project documentation
├── requirements.txt             # Python dependencies (if added)
└── data/                        # (Optional) Dataset folder
```

---

## ⚙️ Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/decision-tree-scratch.git
   cd decision-tree-scratch
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🛠️ Usage  

1. Open the notebook:  
   ```bash
   jupyter notebook DecisionTreeScratch.ipynb
   ```

2. Run all cells to:  
   - Preprocess the dataset  
   - Train the decision tree model  
   - Predict outputs for test samples  

3. Example usage (inside notebook):  
   ```python
   model = DecisionTree()
   model.fit(X_train, y_train)
   prediction = model.predict(X_test[0])
   print(prediction)
   ```

---

## 📊 Results  
- Demonstrates how decision trees split data recursively.  
- Helps in understanding **overfitting** and the role of stopping criteria.  
- Accuracy depends on dataset and chosen splitting metric.  

---

## 🔮 Future Improvements  
- Add pruning methods to avoid overfitting.  
- Extend to **Random Forest** implementation.  
- Visualize the tree structure graphically.  

---

## 🤝 Contributing  
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.  

---

## 📜 License  
This project is licensed under the MIT License.  
