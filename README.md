# Disease Prediction using Machine Learning

This BDA (Big Data Analytics) project predicts diseases based on user input using four popular machine learning algorithms:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes

The project includes a simple **Tkinter GUI** for user interaction.

---

## Algorithms Used

- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes Classifier**

These algorithms are trained on medical data to predict potential diseases based on symptoms or input features.

---

## 🛠 Requirements

Ensure the following Python libraries are installed:

```bash
pip install pandas numpy scikit-learn
```
Tkinter is usually included with Python. If not:
Ubuntu/Debian:
```bash
sudo apt-get install python3-tk
```
Windows: Tkinter is included with Python installations.

## Dataset
The project uses a structured dataset containing symptom inputs and corresponding disease labels.

Replace this section with actual dataset details if you're using a public or proprietary dataset.

## Notes
Ensure the dataset is cleaned and encoded for best results.
You can modify the models.py file to adjust model parameters or add feature engineering steps.

## How to Run
Follow these steps to run the project:

1. Clone the Repository
```bash
git clone https://github.com/yourusername/disease-prediction-ml.git
cd disease-prediction-ml
```
2. Install Required Libraries
```bash
pip install pandas numpy scikit-learn
```
3. Run the Application
```bash
python main.py
```
The Tkinter GUI will launch. Enter your symptoms or data inputs, and the system will provide disease predictions using all four machine learning algorithms.
