
# Stress-Strain Prediction for Stainless Steel Nanowires using Machine Learning

This project uses machine learning models to predict the stress–strain behavior of stainless steel nanowires subjected to extreme strain rates and elevated temperatures. The goal is to accelerate materials research by replacing costly and time-consuming experiments with accurate predictive models.

## 🚀 Project Highlights

- **Domain:** Materials Science / Mechanical Behavior Prediction  
- **Data:** High-fidelity simulation dataset including:
  - Strain rates: 5×10⁷ – 1×10⁹ s⁻¹  
  - Temperatures: 450–650 K  
  - Features: Composition, crystallite size, cooling rate  
- **Target:** Predict full stress–strain curves and yield strength

## 🧠 Machine Learning Models

Implemented and benchmarked six regression algorithms:

- ✅ Extreme Gradient Boosting (XGBoost)
- ✅ Gradient Boosting Regressor
- ✅ Random Forest
- ✅ Decision Tree

### 📈 Best Model Performance
- **Gradient Boosting**: Achieved up to **97.6% $R^2$**
- **XGBoost & ANN**: ~96% $R^2$
- **Other models**: ~86% $R^2$

## 📂 Project Structure

```
stress-strain-prediction/
├── data/                      # Raw and processed data files
├── notebooks/                 # Jupyter notebooks for EDA, modeling
├── models/                    # Trained model files
├── src/                       # Source code (data loading, ML pipeline)
├── results/                   # Model outputs, plots, metrics
├── README.md                  # Project overview
├── requirements.txt           # Python dependencies
└── LICENSE
```

## 📊 Example Results

Plots and comparisons between predicted vs. actual stress–strain curves across different strain rates and temperatures demonstrate strong model generalization.

![example-plot](results/stress_strain_plot.png)

## 💡 Key Outcomes

- Accurately predicted complex elastic-plastic behavior, flow softening, and strain localization.
- Reduced the need for costly simulations and experiments by over 80%.
- Enabled faster exploration of how microstructural and thermal parameters affect mechanical properties.

## 🔧 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/gurjot108/stress-strain-prediction.git
   cd stress-strain-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run a notebook or script:
   ```bash
   jupyter notebook notebooks/model_training.ipynb
   ```

## 🛠️ Tech Stack

- Python, NumPy, Pandas, Matplotlib
- Scikit-learn, XGBoost
- Jupyter Notebooks

## 📜 License

This project is licensed under the MIT License.

---

**Contact**: [gurjotsingh810@gmail.com]  
**GitHub**: [github.com/gujrot108](https://github.com/gurjot108)
