# EchoGuard: Sonar Rock vs. Mine Classifier 🌊🛡️

**EchoGuard** is an introductory machine learning project focused on binary classification. It uses a **Logistic Regression** model to distinguish between sonar signals bounced off a metal cylinder (representing a mine) and those bounced off a rock.

As an initial ML project, it serves as a practical exercise in implementing a complete machine learning workflow, from data exploration and preprocessing to model training and evaluation.

The model achieves an accuracy of approximately **76%** on the test data.

## 🎯 Project Goal

The primary objective is to build a predictive model that can accurately classify underwater objects as either a **Rock** or a **Mine** based on sonar return data.

## 📊 Dataset

The project utilizes the "Sonar, Mines vs. Rocks" dataset, which contains 208 data points. Each data point is a set of 60 numbers representing the energy in different frequency bands, recorded from sonar signals bounced off objects at various angles.

-   **Features**: 60 sonar signal readings.
-   **Target**: `R` (Rock) or `M` (Mine).

## ⚙️ Technology Stack

-   **Data Analysis**: Pandas, NumPy
-   **Data Visualization**: Matplotlib, Seaborn
-   **Machine Learning**: Scikit-learn
-   **Development Environment**: Jupyter Notebook

## 🚀 Project Workflow

1.  **Data Loading & Inspection**: The dataset is loaded, and an initial analysis is performed to understand its structure and characteristics.
2.  **Data Preprocessing**: The categorical target labels ('R' and 'M') are converted into numerical format for the model.
3.  **Train-Test Split**: The data is split into training and testing sets to evaluate the model's performance on unseen data.
4.  **Model Training**: A **Logistic Regression** model is instantiated and trained on the training dataset.
5.  **Prediction & Evaluation**: The trained model makes predictions on both the training and test data. The model's accuracy is then calculated to assess its performance.

## 📈 Results & Future Work

-   **Test Data Accuracy**: ~76%

This project provides a solid foundation in classification. Future work could involve:
-   Trying more advanced classification algorithms (e.g., SVM, Random Forest, Gradient Boosting).
-   Implementing cross-validation for more robust evaluation.
-   Performing hyperparameter tuning to optimize model performance.

## 🛠️ How to Run this Project

### Prerequisites

-   Python 3.x
-   Jupyter Notebook or JupyterLab

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/Jdrao7/EchoGuard.git](https://github.com/Jdrao7/EchoGuard.git)  cd EchoGuard
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```sh
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```

4.  **Launch Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```

5.  **Run the notebook:**
    -   Open and execute the cells in the `Sonar rock vs mine prediction.ipynb` file.
