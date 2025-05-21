# *Workforce Departure Prediction*
🎯 An Ensemble Learning Approach for Predicting Voluntary Employee Attrition Using Machine Learning and Deep Learning Models

## 📌 Overview
Employee attrition poses a major challenge for modern organizations, leading to increased hiring costs, lowered productivity, and lost expertise. This project aims to address this challenge using an ensemble learning model that combines Logistic Regression, Random Forest, and Artificial Neural Network to enhance the precision of attrition prediction.

The model uses structured HR data to identify employees who are likely to leave the organization, helping HR teams make proactive retention decisions.

## 🧠 Problem Statement
Traditional methods of attrition analysis are reactive and lack predictive power. The goal of this project is to build a predictive system that can:

Identify employees likely to leave.

Interpret which features contribute to this decision.

Provide an interactive interface for real-time prediction.

## 🛠️ Tech Stack
<ul>
  
<li> <b>Programming Language: Python 🐍</b></li>

<li> <b>Framework: Flask 🌐</b></li>

<li> <b>Frontend: HTML/CSS/JS </b></li>

<li> <b>Backend: MySQL 🗃️</b></li>

<li> <b>Machine Learning Libraries: scikit-learn, XGBoost, Keras, TensorFlow</b></li>

<li> <b>Visualization: Matplotlib, Seaborn, SHAP</b></li>

<li> <b>Deployment: Local Server & Static on Render</b></li>
</ul>


## 🧪 Models Used
<li> <b>📉 Logistic Regression (Baseline model, interpretable)</b></li>

<li> <b>🌲 Random Forest (Robust and non-linear)</b></li>

<li> <b>🧠 Artificial Neural Network (Deep learning model for pattern recognition)</b></li>

<li> <b>🧬 Ensemble Logic: Average of predictions or majority vote from the above three models</b></li>

## 📊 Dataset
<li> <b>Source: IBM HR Analytics Employee Attrition Dataset

<li> <b>Records: 1,470 employees

<li> <b>Features: 30+ features including age, job satisfaction, monthly income, promotion history, and work-life balance.

<li> <b>Target: Attrition (Yes/No)

## ⚙️ Features
💡 Dynamic model selection based on user input.

🔍 SHAP values for interpretability.

📈 Visual insights via EDA.

✅ Trained models with metrics: Accuracy, Precision, Recall, F1-Score.

🖥️ User-friendly web interface to input employee details and get prediction.

<h2>🚀 How to Run Locally</h2>
<ol>
  <li>Clone the repository:</li>
</ol>

<pre>
git clone https://github.com/yourusername/workforce-departure-prediction.git
cd workforce-departure-prediction
</pre>

<ol start="2">
  <li>Install dependencies:</li>
</ol>

<pre>
pip install -r requirements.txt
</pre>

<ol start="3">
  <li>Start the Flask server:</li>
</ol>

<pre>
python app.py
</pre>

<ol start="4">
  <li>Visit <a href="http://127.0.0.1:5000">http://127.0.0.1:5000</a> in your browser</li>
</ol>

<hr>

<h2>📈 Model Performance</h2>

<table>
  <tr>
    <th>Model</th>
    <th>Accuracy</th>
    <th>Precision</th>
    <th>Recall</th>
    <th>F1-Score</th>
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>84.2%</td>
    <td>71.3%</td>
    <td>67.8%</td>
    <td>69.5%</td>
  </tr>
  <tr>
    <td>Random Forest</td>
    <td>88.1%</td>
    <td>79.5%</td>
    <td>73.4%</td>
    <td>76.3%</td>
  </tr>
  <tr>
    <td>ANN</td>
    <td>86.7%</td>
    <td>76.1%</td>
    <td>71.0%</td>
    <td>73.4%</td>
  </tr>
  <tr>
    <td><strong>Ensemble (Voting)</strong></td>
    <td><strong>89.2%</strong></td>
    <td><strong>81.2%</strong></td>
    <td><strong>75.6%</strong></td>
    <td><strong>78.3%</strong></td>
  </tr>
</table>


## 💬 Future Work
<ul>
  <li>🎯 Integration of real-time HRMS data</li>
  <li>📚 Expansion to attrition cause classification</li>
  <li>☁️ Cloud deployment Render</li>
  <li>🔐 Add HR login, session tracking & audit logs</li>
</ul>
<hr>

<h2>🤝 Contributors</h2>
<ul>
  <li><strong>Name:</strong> Raman Raj Singh</li>
  <li><strong>College:</strong> College of Technology and Engineering, MPUAT</li>
  <li><strong>Internship:</strong> SSPL-DRDO,Advaiya Solutions Pvt. Ltd.</li>
  <li><strong>Skills:</strong> Python, Flask, ML, GitHub</li>
</ul>

<hr>

<h2>📄 License</h2>
<p>This project is licensed under the <strong>MIT License</strong>.</p>
