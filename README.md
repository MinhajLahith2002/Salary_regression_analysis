# Salary Regression Analysis

This project explores regression techniques to predict salary based on position level using a small dataset. It compares the performance of **Simple Linear Regression** and **Polynomial Regression** models of varying degrees.

## 📊 Dataset

- **Source**: `w2_position_salaries.csv`
- **Features**:
  - `Level` (numeric): Represents the seniority or rank of a position.
  - `Salary` (numeric): Corresponding salary for the given level.

## 🧠 Models Trained

1. **Simple Linear Regression**
2. **Polynomial Regression**:
   - Degree 2
   - Degree 3
   - Degree 4

> The entire dataset was used for training without splitting into train/test sets, as per task instructions.

## 📈 Evaluation Metric

- **R² Score**: Measures how well the model explains the variance in the salary data.

## ✅ Results

| Model                      | R² Score |
|---------------------------|----------|
| Simple Linear Regression  | 0.669    |
| Polynomial Regression (deg 2) | 0.916    |
| Polynomial Regression (deg 3) | 0.981    |
| Polynomial Regression (deg 4) | 0.997    |

> Polynomial regression models significantly outperform linear regression, but optimal degree selection should ideally use a validation set.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📁 File Structure

- `salary_regression_analysis.py`: Main script for training and evaluation
- `w2_position_salaries.csv`: Dataset file
- `Polynomial Regression.ipynb`: Notebook for polynomial model exploration
- `salary_regression_analysis.ipynb`: Notebook for full pipeline and visualization

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/MinhajLahith2002/Salary_regression_analysis.git
