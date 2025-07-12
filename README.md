# 🎓 Smart University Admission Prediction

A simple web application built with **Streamlit** to predict the chances of admission based on academic scores and research experience using a trained **machine learning model**.

---

## 🧠 Features

* User-friendly web interface to input academic details
* Predicts the likelihood of admission into a university
* Uses pre-trained machine learning model for prediction
* Input values are scaled using a saved scaler for consistency

---

## ⚙️ How It Works

1. The user enters their academic details like GRE score, TOEFL score, SOP, LOR, CGPA, etc.
2. The input is standardized using a pre-trained scaler (`scaler_model.pickle`).
3. A trained model (`finalized_model.pickle`) processes the input and outputs a prediction.
4. The app displays the admission chance as a percentage.

---

## 🧠 Model

* The app uses a pre-trained regression model stored in `finalized_model.pickle`
* A `StandardScaler` (`scaler_model.pickle`) is used to normalize input features

---

## � installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/admission-prediction.git
cd admission-prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

* On **Windows**:

```powershell
.\venv\Scripts\Activate.ps1
```

* On **Mac/Linux**:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the app

```bash
streamlit run main.py
```

Then open: `http://localhost:8501` in your browser.

### ➕ Optional

* Download and extract the files
* Open terminal or Anaconda Prompt in that folder
* Run:

```bash
streamlit run main.py
```

---

## 🎯 Input Parameters

* **GRE Score** (out of 340)
* **TOEFL Score** (out of 120)
* **University Rating** (1 to 5)
* **SOP Strength** (0 to 5)
* **LOR Strength** (0 to 5)
* **CGPA** (out of 10)
* **Research Experience**: Yes/No

---

## 📁 Project Structure

```
.
├── main.py                  # Streamlit app
├── finalized_model.pickle   # Trained ML model
├── scaler_model.pickle      # Pre-trained scaler
├── requirements.txt         # Required packages
├── Admission_Prediction.csv # (Optional) training data
└── README.md                # Project documentation
```

---

## 📦 Requirements

* Python 3.x
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle

Install everything with:

```bash
pip install -r requirements.txt
```

---

## 🙏 Acknowledgements

* Dataset: Admission_Prediction.csv
* ML: Scikit-learn
* Web Interface: Streamlit

---


## ✉️ Contact

Made with ❤️ by **Jaydeep Dalvi**
Feel free to connect on [LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/jaydeep-d-dalvi/)) or [Email](dalvijaydeep3814@gmail.com)

---
