# 📈 Linear Regression From Scratch

This repository contains the implementation of **Simple Linear Regression** and **Multiple Linear Regression** algorithms built entirely from scratch using **Python** and its fundamental libraries (**NumPy** and **Pandas**), without relying on high-level machine learning libraries like `scikit-learn`.

The goal of this project is to provide a deep understanding of the mathematical and algorithmic principles behind Linear Regression.

---

## ✨ Features

* **Simple Linear Regression:** Implementation using the Ordinary Least Squares (OLS) method.
* **Multiple Linear Regression:** Implementation capable of handling multiple features/predictors.
* **Detailed Jupyter Notebooks:** Step-by-step code and explanations for the model construction, training, and prediction processes.
* **Real-world Dataset:** Uses a simple `placement.csv` dataset for demonstration.

---

## 📂 Repository Structure

The project is organized into several Jupyter Notebooks, each focusing on a specific implementation:

| File Name | Description |
| :--- | :--- |
| `simplelinearRegression_from_scratch.ipynb` | The core implementation of Simple Linear Regression using the OLS method. |
| `SimpleLinearRegression.ipynb` | An additional notebook for Simple Linear Regression examples or comparisons. |
| `multiple_linear_regression.ipynb` | Implementation of Multiple Linear Regression. |
| `Sctrach_multiple_linear_regression.ipynb` | Another notebook detailing the steps for Multiple Linear Regression from scratch. (Note: Please check the spelling, it might be a typo for "Scratch"). |
| `placement.csv` | The dataset used across the notebooks for training and evaluation. |

---

## 🛠️ Installation and Setup

To run the notebooks locally, you need a Python environment with Jupyter installed.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Saransh-Basu-01/LinearRegression_from_scratch.git](https://github.com/Saransh-Basu-01/LinearRegression_from_scratch.git)
    cd LinearRegression_from_scratch
    ```

2.  **Install the required dependencies:**
    The notebooks primarily use NumPy and Pandas.
    ```bash
    pip install pandas numpy jupyter
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    This command will open a browser window where you can navigate and open the `.ipynb` files.

---

## 🚀 Usage

Open any of the Jupyter Notebooks (`*.ipynb`) to explore the code. The notebooks are designed to be run sequentially cell-by-cell.

* **Simple Linear Regression:** Focus on calculating the slope and intercept using the formulas derived from minimizing the Sum of  Mean Squared Errors (SSE).
* **Multiple Linear Regression:** Focus on using matrix algebra (e.g., the Normal Equation) to find the optimal weight vector.

Feel free to experiment with the `placement.csv` data or integrate your own dataset into the notebooks.
