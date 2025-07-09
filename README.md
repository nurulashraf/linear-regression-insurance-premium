# Predicting Insurance Premiums using Linear Regression

A simple project demonstrating how to build and evaluate a linear regression model to predict insurance premiums using Python.

---

## Project Structure

- `data/`: Contains the dataset used.
- `notebooks/`: Main Jupyter Notebook folder containing data preprocessing, model training, and prediction steps.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project documentation.

---

## Features

- Load and explore an insurance dataset
- Clean and preprocess data
- Build a simple linear regression model
- Visualise results and performance metrics
- Save outputs for review

---

## Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/nurulashraf/linear-regression-insurance-premium.git
   cd linear-regression-insurance-premium
   ````

2. **Set up a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook**

   ```bash
   jupyter notebook notebooks/insurance_premium_analysis.ipynb
   ```

   Or run the Python scripts:

   ```bash
   python src/data_preprocessing.py
   python src/model_training.py
   python src/model_evaluation.py
   ```

---

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
