# PCOS Detection Application

This is a machine learning-based application for detecting Polycystic Ovary Syndrome (PCOS) using clinical and physical parameters.

## Project Structure

pcos detection/
│
├── app.py # Main application script
├── pcosdetection.ipynb # Jupyter notebook (exploration/training)
├── PCOS_data_without_infertility.xlsx # Dataset used
├── random_forest_pcos_18_features.pkl # Trained ML model
├── final research paper.docx # Research documentation
├── Final_Report.pdf # Final report
├── Final_Presentation.pdf # Project presentation
└── .gitignore



## Requirements

Before running the application, make sure you have Python installed. Then, install the required Python packages using:

```bash
pip install -r requirements.txt

If requirements.txt is missing, install dependencies manually:
pip install flask flask-mysqldb joblib pandas numpy matplotlib seaborn scikit-learn werkzeug openpyxl


How to Run
To start the Flask application:python app.py
By default, the application will run on http://127.0.0.1:5000/.


Usage
Once the app is running:

Open your browser and go to http://127.0.0.1:5000/.

Upload input data or fill in clinical features to receive PCOS predictions.

Notes
Make sure random_forest_pcos_18_features.pkl is present in the same directory as app.py.

The model expects 18 clinical features as input.

The dataset PCOS_data_without_infertility.xlsx is used only for reference/training, not needed for predictions.


5. Press `Ctrl + S` to save the file.

---

## 📄 Step 3: Create `requirements.txt`

1. Again, right-click inside the project folder in VS Code.
2. Select **New File**.
3. Name it exactly: `requirements.txt`
4. Paste this content into the file:

```txt
flask
flask-mysqldb
joblib
numpy
pandas
matplotlib
seaborn
scikit-learn
werkzeug
openpyxl



