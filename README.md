# Predicting and Interpreting Oxide Glass Properties 🧪 | Machine Learning

This project focuses on predicting and interpreting the properties of oxide glasses using machine learning techniques.  
The goal is to estimate material properties (like Young’s Modulus) from a given chemical composition and provide explainability for the predictions.

---

## 🔑 Features
- Predicted and interpreted oxide glass properties from chemical composition data.
- Implemented **Ensemble Modelling** using:
  - XGBoost
  - CatBoost
  - LightGBM
- Achieved improved accuracy compared to the reference research paper.
- For **Young’s Modulus**:
  - Author’s R² Score: **0.920**
  - Ensemble Model R² Score: **0.938**
- Used **SHAP (Shapley Additive Explanations)** for model interpretability.

---

## ⚙️ Tech Stack
- **Programming Language**: Python  
- **Machine Learning Libraries**: XGBoost, CatBoost, LightGBM  
- **Explainability Tool**: SHAP  
- **Environment**: Jupyter Notebook  

---

## 🚀 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/oxide-glass-ml.git
   cd oxide-glass-ml
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 📂 Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook AI_ProjectAbeeNumber.ipynb
   ```
2. Run all cells to train the models and generate predictions.
3. Explore SHAP visualizations to interpret model behavior.

---

## 📊 Results
- The ensemble model outperformed the baseline results reported in the research paper.  
- **Young’s Modulus** prediction showed significant improvement with an R² score of **0.938**.

---

## 📖 Learning Outcomes
- Application of ensemble learning models in materials science.
- Improved model accuracy through boosting techniques.
- Model interpretability using **SHAP**.

---

## 👤 Author
- **Your Name**  
- Machine Learning & Data Science Enthusiast  

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
