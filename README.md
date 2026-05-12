<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <header><h1>🚀 Multiple Linear Regression — OOP Implementation with Flask Deployment</h1></header>

  <section>
    <h2>📌 Project Overview</h2>
    <p>
      A complete, production-style implementation of <strong>Multiple Linear Regression</strong> using Object-Oriented Programming (OOP) in Python, trained on the <code>50_Startups.csv</code> dataset, and served through a Flask web application.
    </p>
    <ul>
      <li>Encapsulation of ML pipeline in a single class</li>
      <li>Exception handling with detailed diagnostics</li>
      <li>Model persistence with Pickle</li>
      <li>Interactive Flask web interface</li>
    </ul>
  </section>

  <section>
    <h2>🧠 What is Multiple Linear Regression?</h2>
    <p>
      Multiple Linear Regression (MLR) models the relationship between one dependent variable (Profit) and multiple independent variables (R&D, Administration, Marketing, State).
    </p>
    <ul>
      <li>Predicting house prices</li>
      <li>Estimating startup profits</li>
      <li>Forecasting sales</li>
      <li>Predicting salaries</li>
    </ul>
  </section>

  <section>
    <h2>📐 Mathematical Foundation</h2>
    <p>
      Equation:<br><br>
      <code>Profit = β₀ + β₁(R&D Spend) + β₂(Administration) + β₃(Marketing Spend) + β₄(State) + ε</code>
    </p>
  </section>

  <section>
    <h2>📊 Dataset Description</h2>
    <p>File: <code>50_Startups.csv</code></p>
    <ul>
      <li>R&D Spend — Float</li>
      <li>Administration — Float</li>
      <li>Marketing Spend — Float</li>
      <li>State — String → Integer (NY=0, CA=1, FL=2)</li>
      <li>Profit — Float (Target)</li>
    </ul>
  </section>

  <section>
    <h2>🗂️ Project Structure</h2>
    <pre>
MLR_OOPS_Code/
│── main.py             # Core ML pipeline using OOP
│── app.py              # Flask backend
│── 50_Startups.csv     # Dataset
│── Model.pkl           # Trained model
│── templates/index.html# Frontend form
└── README.html         # Documentation
    </pre>
  </section>

  <section>
    <h2>⚙️ Installation & Usage</h2>
    <pre><code>git clone https://github.com/yourusername/MLR_OOPS_Code.git
cd MLR_OOPS_Code
pip install -r requirements.txt
python main.py
python app.py</code></pre>
    <p>Open in browser: <strong>http://127.0.0.1:5000/</strong></p>
  </section>

  <section>
    <h2>🎯 Sample Prediction</h2>
    <p><strong>Input:</strong> R&D=1200, Admin=1800, Marketing=1900, State=1 (California)</p>
    <p><strong>Output:</strong> Predicted Profit: <span style="color:#00ffcc;font-weight:bold;">$120,000+</span></p>
  </section>

  <section>
    <h2>📈 Evaluation Metrics</h2>
    <ul>
      <li>R² Score — closer to 1 = better</li>
      <li>RMSE — lower = better accuracy</li>
      <li>Compare Train vs Test to detect overfitting</li>
    </ul>
  </section>

  <section>
    <h2>🛠️ Technologies Used</h2>
    <ul>
      <li>Python 3.8+</li>
      <li>NumPy, Pandas</li>
      <li>scikit-learn</li>
      <li>Flask</li>
      <li>Pickle</li>
      <li>Bootstrap (Frontend)</li>
    </ul>
  </section>

  <section>
    <h2>📬 Contact & Support</h2>
    <p><strong>Author:</strong> S. Lakshmi Kaveri</p>
    <p>💼 LinkedIn: <a href="https://www.linkedin.com/in/kaveri03/" target="_blank">Your LinkedIn</a></p>
    <p>🐙 GitHub: <a href="https://github.com/kaveri93" target="_blank">Your GitHub</a></p>
    <p>📧 Email: sankathalalakshmikaveri93@gmail.com</p>
  </section>

  <div class="footer">
    📄 License: MIT | Built with ❤️ by S. Lakshmi Kaveri
  </div>
</body>
</html>


