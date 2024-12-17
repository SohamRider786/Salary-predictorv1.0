# Simple Linear Regression Model for Predicting Salaries

This repository contains a Python implementation of a simple linear regression model to predict salaries based on years of experience. The model is built using libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-Learn**.

---

## Features

- **Data Handling**: Loads and preprocesses data from `Salary_Data.csv`.
- **Model Training**: Trains a linear regression model using Scikit-Learn.
- **Visualization**: Provides visual insights into the training and test results using Matplotlib.

---

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Required Python libraries:
  ```bash
  pip install pandas numpy matplotlib scikit-learn
  ```

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   ```

2. **Prepare the Dataset**:
   - Place the `Salary_Data.csv` file in the root directory of the repository.
   - Ensure the dataset contains two columns:
     - `Years of Experience`: Numerical data representing work experience in years.
     - `Salary`: Corresponding annual salary.

3. **Run the Script**:
   Execute the Python script to train and test the model:
   ```bash
   python salary_prediction.py
   ```

---

## Code Overview

1. **Import Libraries**:
   - The script uses **Pandas** for data handling, **NumPy** for numerical computations, **Matplotlib** for visualization, and **Scikit-Learn** for machine learning tasks.

2. **Data Preparation**:
   - The dataset is split into independent variables (`X`) and dependent variables (`y`).
   - Training and testing sets are created using an 80-20 split.

3. **Model Training**:
   - The script trains a simple linear regression model using the training set.

4. **Visualization**:
   - Training set: A scatter plot of actual salaries and a regression line.
   - Test set: Actual vs. predicted salaries plotted for evaluation.

---

## Visualizations

1. **Training Set Visualization**:
   - The scatter plot shows the actual data points for training.
   - The regression line depicts the relationship learned by the model.

2. **Test Set Visualization**:
   - A scatter plot highlights actual vs. predicted salaries.
   - This provides a visual assessment of the model's performance on unseen data.

---

## Example Output

### Training Set:

![Train](https://github.com/user-attachments/assets/472aaf22-fd51-4599-bf59-38e7d658279a)


### Test Set:

![test](https://github.com/user-attachments/assets/3e4fe03c-b9bb-4e0a-a17a-62b36c7ac84a)


(Replace `#` with links to the images of the visualizations if applicable.)

---

## Contributing

Feel free to contribute to this project by improving the code or adding new features. To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Acknowledgments

This project is a demonstration of simple linear regression using Python for beginners. Special thanks to the open-source community for providing the libraries used in this project.

