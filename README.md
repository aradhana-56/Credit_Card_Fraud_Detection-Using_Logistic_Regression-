<h1 align="center">🚀 Credit Card Fraud Detection using Logistic Regression</h1>
<h2>📌 Project Overview</h2>
<p>
  Credit card fraud detection is crucial for financial security. This project applies <b>Logistic Regression</b> to classify transactions as fraudulent or legitimate.
  Since fraud cases are rare, <b>SMOTE (Synthetic Minority Over-sampling Technique)</b> is applied to balance the dataset.
</p>

<h2>📂 Dataset Information</h2>
<ul>
  <li><b>Source:</b> <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Kaggle - Credit Card Fraud Detection</a></li>
  <li><b>Features:</b> Time, Amount, V1-V28 (PCA-transformed)</li>
  <li><b>Target:</b> Class (0 = Legitimate, 1 = Fraudulent)</li>
</ul>

<h2>🛠️ Setup Instructions</h2>
<h3>1️⃣ Install Dependencies</h3>
<pre>
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn joblib
</pre>

<h3>2️⃣ Download the Dataset</h3>
<p>Ensure <code>creditcard.csv</code> is placed in the working directory.</p>

<h3>3️⃣ Run the Model</h3>

<h2>📊 Data Preprocessing & Feature Engineering</h2>
<ul>
  <li><b>Scaling Features:</b> Using <code>StandardScaler</code></li>
  <li><b>Handling Imbalance:</b> Using <code>SMOTE</code></li>
  <li><b>Train-Test Split:</b> 80% training, 20% testing</li>
</ul>

<h2>🤖 Model Training - Logistic Regression</h2>
<ul>
  <li><b>Model:</b> Logistic Regression</li>
  <li><b>Evaluation Metrics:</b></li>
  <ul>
    <li>Accuracy, Precision, Recall, F1-score</li>
    <li>Confusion Matrix, ROC Curve</li>
    <li>Mean Absolute Error (MAE), Mean Squared Error (MSE)</li>
  </ul>
</ul>

<h2>📈 Model Performance</h2>
<table>
  <tr>
    <th>Metric</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>Accuracy</td>
    <td><b>95%</b></td>
  </tr>
  <tr>
    <td>Precision</td>
    <td><b>0.97</b></td>
  </tr>
  <tr>
    <td>Recall</td>
    <td><b>0.92</b></td>
  </tr>
  <tr>
    <td>AUC-ROC</td>
    <td><b>0.95</b></td>
  </tr>
  <tr>
    <td>MAE</td>
    <td><b>0.04</b></td>
  </tr>
  <tr>
    <td>MSE</td>
    <td><b>0.04</b></td>
  </tr>
</table>

<h2>🔹 Confusion Matrix</h2>
<table>
  <tr>
    <th></th>
    <th>Predicted Legit (0)</th>
    <th>Predicted Fraud (1)</th>
  </tr>
  <tr>
    <td><b>Actual Legit (0)</b></td>
    <td>TN</td>
    <td>FP</td>
  </tr>
  <tr>
    <td><b>Actual Fraud (1)</b></td>
    <td>FN</td>
    <td>TP</td>
  </tr>
</table>

<h2>📦 Model Deployment</h2>


<h2>📚 References</h2>
<ul>
  <li><a href="https://scikit-learn.org/">Scikit-Learn Documentation</a></li>
  <li><a href="https://imbalanced-learn.org/">Imbalanced-Learn Documentation</a></li>
</ul>

<h2>👨‍💻 Author</h2>
<p>🚀 <b>Aradhana Patra</b> | 🌍 GitHub: <a href="https://github.com/aradhana-56">GitHub</a> |  🔗 LinkedIn: <a href="https://www.linkedin.com/in/aradhana-patra-8694642b5">LinkedIn</a></p>
