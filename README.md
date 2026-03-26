# Car Price Predictor 🚗💰

An end-to-end Machine Learning web application that predicts the selling price of used cars based on various features. 

## 📌 Overview
Selling a used car and not sure what price to ask for? This project uses a **Linear Regression** machine learning model to estimate the value of a car based on historical data. It features a fully functional web interface where users can input car details and get an instant price prediction.

## 🚀 Features
* **Accurate Predictions:** Trained on a comprehensive dataset of used cars.
* **Interactive UI:** Clean, responsive web form to easily input car details.
* **Dynamic Dropdowns:** Car models dynamically update based on the selected car company using JavaScript.
* **Real-time Processing:** Connects the HTML frontend to the Python/Flask backend for seamless predictions.

## 🛠️ Tech Stack
* **Machine Learning:** Python, Scikit-Learn (Linear Regression), Pandas, NumPy
* **Backend:** Flask
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap

## 📊 Dataset & Features Used
The model takes the following inputs to predict the price:
1. **Company:** The brand of the car (e.g., Maruti, Honda, Ford).
2. **Model:** The specific model of the car.
3. **Year of Purchase:** The year the car was originally bought.
4. **Fuel Type:** Petrol, Diesel, or LPG.
5. **Kilometers Driven:** Total distance the car has traveled.

## 💻 Installation & Setup

To run this project locally on your machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/HMBadgujar/car-price-predictor.git](https://github.com/your-username/car-price-predictor.git)
   cd car-price-predictor
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask server:**
   ```bash
   python app.py
   ```

5. **Open your browser:**
   Navigate to `http://127.0.0.1:5000/` to use the application.
