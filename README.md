<h1>Fraud Detection Model</h1>

<h3>Description</h3>
<p>This project focuses on building a machine learning model to detect fraudulent transactions in a financial dataset. The dataset contains over 6 million records and includes transaction information like amount, type, and account balances. The solution utilizes a Random Forest Classifier and includes data cleaning, feature engineering, and model evaluation. Insights derived from the model are also used to suggest actionable fraud prevention strategies.</p>

<h3>Features</h3>
<ul>
  <li><strong>Data Cleaning</strong>: Handles outliers, encodes categorical features, drops non-informative identifiers, and checks for multicollinearity.</li>
  <li><strong>Fraud Detection Model</strong>: Trains a Random Forest Classifier to distinguish fraudulent transactions from legitimate ones.</li>
  <li><strong>Performance Evaluation</strong>: Uses classification report, confusion matrix, and ROC-AUC score to evaluate model performance.</li>
  <li><strong>Feature Importance Analysis</strong>: Identifies and visualizes key factors that contribute to fraud prediction.</li>
  <li><strong>Business Insights</strong>: Offers interpretations of important fraud indicators and suggests infrastructure improvements for fraud prevention.</li>
</ul>

<h3>Key Insights</h3>
<ul>
  <li>Transactions with types such as <strong>TRANSFER</strong> and <strong>CASH_OUT</strong> are most commonly associated with fraud.</li>
  <li>Fraudulent transactions often involve zero balances either before or after the transaction.</li>
  <li>High transaction amounts with unusual patterns are strong fraud indicators.</li>
</ul>

<h3>Fraud Prevention Strategies</h3>
<ul>
  <li>Set up real-time alerts for suspicious transaction types and zero-balance transitions.</li>
  <li>Establish threshold rules for high-value transfers.</li>
  <li>Enforce strict KYC and identity linking policies to reduce dummy accounts.</li>
  <li>Monitor behavioral patterns per customer using historical transaction baselines.</li>
</ul>

<h3>Post-Implementation Monitoring</h3>
<ul>
  <li>Conduct A/B testing with and without fraud detection system rules.</li>
  <li>Compare fraud rate trends before and after infrastructure updates.</li>
  <li>Use user feedback and false positive rates to fine-tune alerts.</li>
</ul>

<h3>Technologies Used</h3>
<ul>
  <li><strong>Python</strong>: Data analysis and model building</li>
  <li><strong>Pandas, NumPy</strong>: Data preprocessing and manipulation</li>
  <li><strong>Matplotlib, Seaborn</strong>: Visualization and insights</li>
  <li><strong>Scikit-learn</strong>: Model training, evaluation, and feature importance</li>
  <li><strong>SciPy</strong>: Outlier detection using Z-score</li>
</ul>

<h3>Project Files</h3>
<ul>
  <li><strong>fraud_detection_notebook.ipynb</strong>: Contains all the steps from data cleaning to evaluation and insights.</li>
  <li><strong>fraud_dataset.csv</strong>: Dataset used for training and testing.</li>
  <li><strong>README.md</strong>: Project documentation.</li>
  <li><strong>requirements.txt</strong>: Python dependencies.</li>
</ul>


