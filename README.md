<h1>🩺 Breast Cancer Diagnosis Prediction using AdaBoost</h1>

<h2>🚀 Live Demo</h2>
<p>
    🔗 <strong>Deployed Application:</strong><br>
    <a href="https://breast-cancer-diagnosis-prediction-using.onrender.com/" target="_blank">
        https://breast-cancer-diagnosis-prediction-using.onrender.com/
    </a>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
This project is an end-to-end <strong>Machine Learning–based web application</strong> that predicts whether a breast tumor is
<strong>Benign (Non-Cancerous)</strong> or <strong>Malignant (Cancerous)</strong> using the
<strong>AdaBoost ensemble learning algorithm</strong>.
</p>

<p>
The trained model is integrated into a <strong>Flask web application</strong> and deployed online using
<strong>Render</strong>, allowing users to perform real-time cancer diagnosis predictions through a clean and interactive UI.
</p>

<hr>

<h2>🧠 Problem Statement</h2>
<p>
Breast cancer is one of the most common cancers worldwide. Early and accurate diagnosis plays a crucial role in effective
treatment and survival rates. Manual diagnosis can be time-consuming and prone to human error.
</p>

<p>
This project aims to assist in medical diagnosis by leveraging machine learning techniques to analyze tumor characteristics
and provide reliable predictions.
</p>

<hr>

<h2>📊 Dataset Description</h2>
<p>
The model is trained using the <strong>Breast Cancer Wisconsin (Diagnostic) Dataset</strong>, which consists of:
</p>

<ul>
    <li><strong>569 patient samples</strong></li>
    <li><strong>30 numerical features</strong> describing tumor characteristics</li>
    <li><strong>Target variable:</strong> Diagnosis (Benign / Malignant)</li>
</ul>

<p>
The 30 features are grouped into:
</p>

<ul>
    <li><strong>Mean Features (10)</strong></li>
    <li><strong>Standard Error Features (10)</strong></li>
    <li><strong>Worst Features (10)</strong></li>
</ul>

<hr>

<h2>⚙️ Machine Learning Model</h2>
<p>
The project uses the <strong>AdaBoost (Adaptive Boosting) Classifier</strong>, an ensemble learning algorithm that combines
multiple weak learners to form a strong classifier.
</p>

<p>
AdaBoost works by giving higher importance to misclassified samples in each iteration, which helps improve overall model
performance and accuracy.
</p>

<p>
After training and evaluation, the final model is serialized using <strong>pickle</strong> and saved as:
</p>

<pre><code>adab.pkl</code></pre>

<hr>

<h2>🌐 Web Application Workflow</h2>
<ol>
    <li>User enters 30 medical input values through the web interface.</li>
    <li>Flask receives the input via POST request.</li>
    <li>Inputs are converted into a NumPy array.</li>
    <li>The trained AdaBoost model predicts the diagnosis.</li>
    <li>The result (Benign or Malignant) is displayed on the UI.</li>
</ol>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
    <li><strong>Programming Language:</strong> Python</li>
    <li><strong>Machine Learning:</strong> Scikit-learn (AdaBoost Classifier)</li>
    <li><strong>Backend:</strong> Flask</li>
    <li><strong>Frontend:</strong> HTML, CSS (Google-style responsive UI)</li>
    <li><strong>Deployment:</strong> Render</li>
</ul>

<hr>

<h2>✨ Features</h2>
<ul>
    <li>End-to-end machine learning pipeline</li>
    <li>Uses all 30 diagnostic features</li>
    <li>Real-time cancer diagnosis prediction</li>
    <li>Clean, modern, and responsive web interface</li>
    <li>Fully deployed and accessible online</li>
</ul>

<hr>

<h2>📁 Project Structure</h2>
<pre>
Breast-Cancer-Diagnosis-Prediction-using-AdaBoost/
│
├── app.py                  # Flask backend
├── adab.pkl                # Trained AdaBoost model
├── templates/
│   └── index.html          # Frontend UI
├── requirements.txt        # Dependencies
├── notebook.ipynb          # Model training & analysis
└── README.md               # Project documentation
</pre>

<hr>

<h2>🎯 Conclusion</h2>
<p>
This project demonstrates the complete lifecycle of a machine learning application — from data analysis and model training
to deployment as a live web application.
</p>

<p>
It serves as a strong portfolio project showcasing skills in:
</p>

<ul>
    <li>Machine Learning</li>
    <li>Ensemble Algorithms</li>
    <li>Flask Web Development</li>
    <li>Model Deployment</li>
</ul>

<p>
The application can be further enhanced by adding prediction probabilities, model evaluation metrics, and advanced UI
features.
</p>
