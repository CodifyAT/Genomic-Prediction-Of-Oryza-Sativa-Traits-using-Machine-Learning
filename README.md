# Genomic-Prediction-Of-Oryza-Sativa-Traits-using-Machine-Learning

[Link To Website](https://agrigen.onrender.com)

Welcome to the Genomic Prediction of Oryza Sativa Traits project! 🌾 This project aims to predict crucial rice phenotypes, like plant height and yield, by analyzing genomic sequences using advanced machine learning models. Whether you’re a data scientist, a genomic researcher, or just someone curious about how machine learning can be applied in agriculture, this project is for you!

Why Do You Need This Project?

Predicting the traits of rice (Oryza Sativa) can significantly impact agriculture, from enhancing crop yields to ensuring food security. By leveraging machine learning, we can analyze complex genomic data and make accurate predictions, helping farmers and researchers make informed decisions. Imagine being able to forecast the potential height or yield of a rice crop before it even grows - that’s the power of this project!

Features

	•	🌱 Predict rice phenotypes based on genomic sequences.
	•	🧠 Utilizes Random Forest and Decision Trees for accurate predictions.
	•	💻 Full-stack web application with a user-friendly interface.
	•	📊 Real-time data visualization and prediction results.

Tech Stack

	•	Frontend: HTML, CSS, Bootstrap
	•	Backend: Flask
	•	Machine Learning Models: Random Forest, Decision Trees

Setup and Installation

Ready to dive in? Great! Here’s how you can set up the project on your local machine.

Prerequisites

First things first, you need to have Python installed. We recommend Python 3.x. You’ll also need pip, the Python package installer.


## Installation Steps

1. **Clone the repository:**
  Open your terminal and run:
    ```bash
    git clone https://github.com/CodifyAT/Genomic-Prediction-Of-Oryza-Sativa-Traits-using-Machine-Learning.git
    cd Genomic-Prediction-Of-Oryza-Sativa-Traits-using-Machine-Learning
    ```

2. **Create and activate a virtual environment:**
This helps keep your project dependencies isolated. Run the following commands:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
With your virtual environment activated, install the project’s dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application:**
Start the Flask development server with:
    ```bash
    python app.py
    ```

5. **Open your browser:**

    Navigate to `http://127.0.0.1:5000` in your web browser, and voila! Your app should be running.


Machine Learning Models

In this project, we use two powerful machine learning models:

	•	Random Forest: This ensemble method builds multiple decision trees and merges them together to get a more accurate and stable prediction.
	•	Decision Trees: A simple yet effective method that splits the data into subsets based on the value of input features.

