# California House Price Prediction 🚀

This project is a web application that predicts house prices in California using a linear regression model. The model is trained on the **California Housing** dataset and deployed using a Flask web framework.


> **Why this project?**  
> It demonstrates the end‑to‑end workflow of a machine‑learning project—data exploration, feature engineering, model training, serialization, and deployment—wrapped in an approachable UI.

---

## 📌 Features

| Feature | Description |
|---------|-------------|
| **Predict prices** | Input `median_income`, `house_age`, `total_rooms`, `population` → output predicted median house value. |
| **User‑friendly UI** | Clean Flask front‑end that accepts inputs and displays results instantly. |
| **Jupyter notebook** | `Linear Regression ML Implementation.ipynb` contains a full walkthrough of the data pipeline and model training. |
| **Model artifacts** | The trained `LinearRegression` instance and the corresponding `StandardScaler` are shipped as `regmodel.pkl` and `scaling.pkl`. |

---

## 🛠️ Tech Stack

| Category | Library |
|----------|---------|
| **Language** | Python 3.x |
| **Web Framework** | Flask |
| **Machine Learning** | scikit‑learn |
| **Data Manipulation** | pandas, numpy |
| **Notebook** | Jupyter Notebook |

---

## ⚙️ Installation & Setup

```bash
# 1️⃣  Clone the repository
git clone https://github.com/your-username/California-house-pricing.git
cd California-house-pricing

# 2️⃣  Create a virtual environment
python -m venv venv

# 3️⃣  Activate it
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# 4️⃣  Install dependencies
pip install -r requirements.txt   # (typo fixed from 'requirement.txt')

# 5️⃣  Start the app
python app.py
```

## Usage

1.  Open your web browser and navigate to `http://127.0.0.1:5000`.
2.  Fill in the input fields with the required information (e.g., median income, house age).
3.  Click the "Predict" button to see the predicted house price.
4.  [https://ibb.co/zVKQNXGP]

## Model Development

The machine learning model is a simple linear regression model trained on the California Housing dataset. The entire process of data cleaning, exploratory data analysis, feature engineering, and model training is documented in the `Linear Regression ML Implementation.ipynb` Jupyter Notebook.

The trained model and the scaler are saved as `regmodel.pkl` and `scaling.pkl` respectively.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
