# 🏠 [Boston House Pricing Prediction ](https://bostonhousepricing-pxxt.onrender.com/)


This is my first Data Science project using the **Boston Housing dataset**.  
The goal of the project is to build a machine learning model that predicts house prices based on various features.  

I performed **Exploratory Data Analysis (EDA)**, studied **correlations**, applied **feature scaling**, and built a **Linear Regression model** using pipelines. The model was serialized with **Pickle**, and deployed using **Render**.

---

## 🚀 Project Workflow

1. **Data Understanding**
   - Loaded the Boston Housing dataset.
   - Studied the data structure, columns, and statistical summaries.

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions of features.
   - Checked for missing values and outliers.
   - Used heatmaps and correlation plots to study feature relationships.

3. **Feature Engineering**
   - Applied **StandardScaler** to normalize numerical features.
   - Created a **Pipeline** to streamline preprocessing and model training.

4. **Model Building**
   - Used **Linear Regression** as the baseline predictive model.
   - Trained the model on standardized features for better performance.

5. **Model Persistence**
   - Saved the trained pipeline using **Pickle** for reusability.

6. **Deployment**
   - Deployed the model as a Flask app on **Render**.
   - Exposed an API endpoint to predict house prices.

---

## 🛠️ Tools and Technologies

- Python 3.13
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Pickle
- Flask
- Render (Deployment)
- Git & GitHub for version control

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Jagan515/BostonHousePricing
cd BostonHousePricing
````

Create a virtual environment (with conda):

```bash
conda create -p venv python==3.13 -y
conda activate venv/
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app locally:

```bash
python app.py
```

---

## 🌐 Deployment

The project is deployed on **Render**.
👉 [Live Demo](https://bostonhousepricing-pxxt.onrender.com/)

---

## 📊 Results

* Linear Regression performed well on the dataset after standardization.
* Scaling the features improved model stability and interpretability.
* The app can now predict housing prices based on user input features.

---

## 🤝 Contributing

This is my first Data Science project, and I’m open to feedback, suggestions, and improvements.

Feel free to fork the repo and raise a pull request! 🚀

---

## ✍️ Author

**Jagan Pradhan**
📧 [jaganp515@egmail.com](mailto:jaganp515@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/jaganpradhan) | [GitHub](https://github.com/Jagan515)



