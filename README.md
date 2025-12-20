# Kaggle Notebooks Collection

A collection of Jupyter notebooks for various Kaggle competitions and challenges, featuring machine learning solutions with advanced feature engineering and model optimization techniques.

## 📚 Notebooks

### 1. SpaceShip.ipynb
**Competition**: Spaceship Titanic

A clean feature engineering pipeline for the Spaceship Titanic competition using scikit-learn's `HistGradientBoostingClassifier`.

**Key Features**:
- Parse `PassengerId` into `Group` and `MemberNum`
- Split `Cabin` into `Deck`, `CabinNum`, `Side`
- Comprehensive spending features: `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`, `TotalSpend`, `IsZeroSpend`, `SpendPerAge`
- Group-aware cross-validation using `StratifiedGroupKFold`
- Safe one-hot encoding with `handle_unknown='ignore'`

### 2. connect-x.ipynb
**Competition**: ConnectX

A GPU-accelerated notebook for the ConnectX competition, implementing game-playing strategies and reinforcement learning approaches.

**Key Features**:
- GPU-enabled for faster training
- Advanced game strategy implementation

### 3. optimized_aimo3_notebook.ipynb
**Competition**: AIMO3 (AI Mathematical Olympiad)

Production-ready GPU inference notebook with H100 optimizations for mathematical reasoning tasks.

**Key Features**:
- ✅ Fixed concurrent.futures import issue
- ✅ H100-optimized vLLM parameters
- ✅ Enhanced batch processing with dynamic sizing
- ✅ Production monitoring & observability
- ✅ Memory-efficient KV cache management
- ✅ Optimized GPU inference

### 4. playground-series-diabetis.ipynb
**Competition**: Playground Series - Diabetes Prediction

A machine learning approach for predicting diabetes using tabular data.

### 5. road-accident-risk.ipynb
**Competition**: Playground Series Season 5 Episode 10

Predicting road accident risk scores using advanced feature engineering and ensemble methods.

**Strategy**:
1. Exploratory Data Analysis (EDA)
2. Feature Engineering & Preprocessing
3. Baseline Models (LightGBM, XGBoost, CatBoost)
4. Ensemble Methods

## 🛠️ Technologies & Frameworks

- **Python 3.x**
- **scikit-learn** - Machine learning algorithms and utilities
- **LightGBM** - Gradient boosting framework
- **XGBoost** - Gradient boosting library
- **CatBoost** - Gradient boosting with categorical features support
- **vLLM** - High-performance LLM inference
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Jupyter Notebook** - Interactive development environment

## 🚀 Getting Started

### Prerequisites

```bash
pip install jupyter numpy pandas scikit-learn lightgbm xgboost catboost
```

For GPU-accelerated notebooks:
```bash
pip install vllm torch
```

### Running the Notebooks

1. Clone this repository:
```bash
git clone https://github.com/arec1b0/kaggle-notebooks.git
cd kaggle-notebooks
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open any notebook and run the cells sequentially

### Using with Kaggle

These notebooks are designed to run on Kaggle's platform:
1. Upload to Kaggle Notebooks
2. Enable GPU/TPU if required (check individual notebook requirements)
3. Enable internet access if needed for package installation
4. Run all cells

## 📁 Repository Structure

```
kaggle-notebooks/
├── SpaceShip.ipynb                      # Spaceship Titanic competition
├── connect-x.ipynb                      # ConnectX game competition
├── optimized_aimo3_notebook.ipynb       # AIMO3 mathematical reasoning
├── playground-series-diabetis.ipynb     # Diabetes prediction
├── road-accident-risk.ipynb             # Road accident risk prediction
└── README.md                            # This file
```

## 📊 Competition Links

- [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic)
- [ConnectX](https://www.kaggle.com/competitions/connectx)
- [Kaggle Playground Series](https://www.kaggle.com/competitions)

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or new competition solutions.

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**arec1b0**
- GitHub: [@arec1b0](https://github.com/arec1b0)
- Kaggle: [Profile](https://www.kaggle.com/arec1b0)

---

⭐ Star this repository if you find it helpful!
