# Solar-AI: AI-Powered Solar Panel Fault Detection & Power Prediction

##  Overview

Solar-AI is an end-to-end Artificial Intelligence project designed to improve the efficiency and reliability of solar power systems. The project combines **computer vision** for solar panel fault detection and **machine learning** for solar power generation prediction, helping operators monitor panel health and estimate energy output accurately.

---

##  Features

*  Detects faults in solar panels using deep learning.
*  Predicts solar power generation using machine learning.
*  Interactive dashboard for visualization.
*  Performance metrics and model evaluation.
*  Easy deployment using Streamlit/FastAPI.

---

##  Tech Stack

### Programming Language

* Python

### Machine Learning

* LightGBM
* Scikit-learn

### Deep Learning

* TensorFlow
* Keras
* VGG16 (Transfer Learning)

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib
* Plotly

### Web Application

* Streamlit
* FastAPI
* Uvicorn

---

## 📂 Project Structure

```text
Solar-AI/
│
├── data/                  # Dataset
├── models/                # Saved ML/DL models
├── notebooks/             # Jupyter notebooks
├── src/                   # Source code
│   ├── preprocessing.py
│   ├── prediction.py
│   ├── fault_detection.py
│   └── utils.py
│
├── app.py                 # Streamlit application
├── requirements.txt
├── README.md
└── LICENSE
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/ShashiBhushanRaj/Solar-AI.git
cd Solar-AI
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

##  Running the Project

Start the Streamlit application:

```bash
streamlit run app.py
```

Or run the FastAPI server:

```bash
uvicorn app:app --reload
```

---

##  Model Performance

### Solar Power Prediction

* Model: LightGBM Regressor
* Evaluation Metrics:

  * RMSE
  * MAE
  * R² Score

### Fault Detection

* Model: VGG16 Transfer Learning
* Metrics:

  * Accuracy
  * Precision
  * Recall
  * F1 Score

---

##  Sample Outputs

* Solar panel fault classification
* Predicted power generation graphs
* Interactive dashboard
* Model evaluation plots

---

##  Applications

* Solar farm monitoring
* Predictive maintenance
* Renewable energy analytics
* Smart grid management
* Industrial solar installations

---

##  Future Improvements

* Real-time IoT integration
* Weather API support
* Edge AI deployment
* Mobile application
* Explainable AI (XAI)

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## Author

**Shashi Bhushan Raj**

* Electronics and Communication Engineering
* AI | Machine Learning | Data Science
* GitHub: https://github.com/ShashiBhushanRaj

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
