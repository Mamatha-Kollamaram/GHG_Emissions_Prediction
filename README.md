#  GHG Emissions Prediction

This project predicts greenhouse gas (GHG) emissions based on various input features using a pre-trained machine learning model. The goal is to assist organizations or researchers in estimating emissions using a simple web-based interface powered by **Streamlit**.

>  **This project was developed as part of an AICTE Virtual Internship Program with Shell and Edunet Foundation.**

##  Features

- Predicts GHG emissions using a trained Logistic Regression model.
- Simple and clean UI built using Streamlit.
- Preprocessing and scaling handled via custom utils.
- Uses `.pkl` files for model and scaler loading.

##  Tech Stack

- Python 3.13+
- Streamlit
- scikit-learn
- pandas, numpy
- joblib

##  Folder Structure

```
.
├── app.py                       # Main Streamlit app
├── GHG_Emissions_Prediction.ipynb  # Jupyter Notebook for development
├── models/
│   ├── LR_model.pkl             # Trained Logistic Regression model
│   └── scalar.pkl               # Scaler used during training
├── utils/
│   └── preprocessor.py          # Input preprocessing logic
└── README.md                    # Project overview
```

##  How to Run

Make sure you have Python installed (preferably 3.11+).

1. Clone this repository:

```bash
git clone https://github.com/Mamatha-Kollamaram/GHG_Emissions_Prediction.git
cd GHG_Emissions_Prediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run app.py
```

The app will launch in your browser. Fill in the required fields to get your emission prediction.

##  Input & Output

- **Input:** Various emission-related factors (entered via UI)
- **Output:** Predicted category of GHG emissions

##  Requirements

You can create a `requirements.txt` with the following:

```
streamlit
joblib
pandas
scikit-learn
numpy
```

##  Author

Made with ❤️ by **Mamatha Kollamaram**  
[GitHub Profile](https://github.com/Mamatha-Kollamaram)

---

Feel free to contribute or raise issues if you find any bugs or have suggestions! 🌱
