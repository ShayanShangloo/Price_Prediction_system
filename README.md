# Price_Prediction_system
Here is a clean and informative `README.md` file for your **Home Price Prediction System** project, based on the uploaded files:

---

```markdown
# 🏡 Bangalore Home Price Prediction System

This is a Flask-based machine learning web API that predicts the prices of homes in Bangalore based on input features such as total square feet, number of bedrooms (BHK), number of bathrooms, and location.

---

## 🚀 Features

- Predicts home prices using a trained ML model
- Returns location names dynamically for form population
- REST API built with Flask
- Pre-trained model and data columns loaded from artifacts
- CORS enabled for frontend/backend integration

---

## 🧠 Tech Stack

- Python 3.x
- Flask
- NumPy
- Pickle (for model serialization)
- JSON (for data config)
- Scikit-learn (for ML training – not shown in repo)

````

---

## 📡 API Endpoints

### `GET /get_location_names`
Returns the list of available locations.

**Response**
```json
{
  "locations": ["1st Phase JP Nagar", "Ejipura", ...]
}
````

---

### `POST /predict_home_price`

**Form Data**

* `total_sqft`: Total area in square feet
* `location`: Location name (string)
* `bhk`: Number of bedrooms
* `bath`: Number of bathrooms

**Response**

```json
{
  "estimated_price": 82.35
}
```

---

## ▶️ Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/ShayanShangloo/Price_Prediction_system.git
cd Price_Prediction_system
```

### 2. Install dependencies

```bash
pip install flask numpy
```

### 3. Make sure the `artifacts/` folder contains:

* `banglore_home_prices_model.pickle`
* `columns.json`

### 4. Run the server

```bash
python server.py
```

---

## 🛡️ .gitignore

Files like IDE configs, workspace history, and sensitive artifacts are ignored using `.gitignore`.

---

## 👨‍💻 Author

**Shayan Shangloo**

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

This project was inspired by the Bangalore house price dataset and related data science tutorials.

```

---

Would you like me to save this as a `README.md` file or include extra sections (e.g., demo GIF, deployment instructions, frontend integration)?
```
