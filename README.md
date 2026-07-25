# Student Marks Prediction using Machine Learning

A Machine Learning web application that predicts a student's **Mathematics score** based on demographic and academic information. The project is built using Python, Scikit-learn, Flask, and a modular machine learning pipeline.

---

## 🚀 Features

- Predicts **Mathematics Score** using Machine Learning.
- Interactive Flask web application.
- Modular ML pipeline architecture.
- Data preprocessing using Scikit-learn.
- Feature engineering and preprocessing pipeline.
- Model serialization using Dill.
- Clean and responsive user interface.

---

## 🛠️ Tech Stack

- **Language:** Python 3.11
- **Frontend:** HTML, CSS, Flask
- **Machine Learning:** Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Model Serialization:** Dill

---

## 📂 Project Structure

```
Student-marks-prediction/
│
├── app.py
├── requirements.txt
├── setup.py
├── Dockerfile
├── README.md
│
├── Artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── Notebook_Experiments/
│
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
├── static/
└── catboost_info/
```

---

## ⚡ Installation

### Clone the Repository

```bash
git clone https://github.com/prashanth20261/Student-marks-prediction.git
```

### Go to the Project Folder

```bash
cd Student-marks-prediction
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:8080
```

---

## 🖥️ How It Works

The user enters:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

The trained Machine Learning model processes these inputs and predicts the student's **Mathematics Score**.

---

## 📊 Machine Learning Pipeline

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Prediction using Flask

---

## 🤖 Model Used

- Linear Regression

The model predicts the **Mathematics Score** using Reading Score, Writing Score, and demographic information.

---

## 🔮 Future Improvements

- Predict all three subject scores:
  - Mathematics
  - Reading
  - Writing
- Add more Machine Learning models.
- Hyperparameter tuning.
- Deploy using Docker.
- Deploy on Render or AWS.
- Add performance dashboard and visualizations.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Create a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Prashanth R**

GitHub:
https://github.com/prashanth20261

Email:
prashanth.20261@gmail.com

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.