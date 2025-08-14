# California House Price Prediction

This project is a web application that predicts house prices in California using a linear regression model. The model is trained on the California Housing dataset and deployed using a Flask web framework.

## Features

*   Predicts house prices based on input features such as median income, house age, number of rooms, and population.
*   User-friendly web interface for easy interaction.
*   Includes the Jupyter Notebook with the complete data analysis and model development process.

## Technologies Used

*   **Python:** The core programming language for the project.
*   **Flask:** A lightweight web framework for building the web application.
*   **Scikit-learn:** For building and training the linear regression model.
*   **Pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical operations.
*   **Jupyter Notebook:** For interactive data analysis and model development.

## Installation and Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/California-house-pricing.git
    cd California-house-pricing
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    # source venv/bin/activate  # On macOS/Linux
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirement.txt
    ```

4.  **Run the application:**
    ```bash
    python app.py
    ```
    The application will be running at `http://127.0.0.1:5000`.

## Usage

1.  Open your web browser and navigate to `http://127.0.0.1:5000`.
2.  Fill in the input fields with the required information (e.g., median income, house age).
3.  Click the "Predict" button to see the predicted house price.

## Model Development

The machine learning model is a simple linear regression model trained on the California Housing dataset. The entire process of data cleaning, exploratory data analysis, feature engineering, and model training is documented in the `Linear Regression ML Implementation.ipynb` Jupyter Notebook.

The trained model and the scaler are saved as `regmodel.pkl` and `scaling.pkl` respectively.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
