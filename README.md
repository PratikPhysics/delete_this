# BigMart Sales Prediction: From XML to MySQL to Streamlit

![BigMart Sales](https://img.shields.io/badge/Project-Sales%20Prediction-blue) ![Python](https://img.shields.io/badge/Python-3.8%2B-green) ![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-red) ![MySQL](https://img.shields.io/badge/MySQL-8.0-orange) ![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-1.2-yellow)

A complete end-to-end Machine Learning project that predicts sales for BigMart outlets. The pipeline starts from raw XML files, moves through MySQL database storage, then into Python for preprocessing, model training, and finally deploys a prediction app using Streamlit.

---

## 📖 Overview

This project demonstrates a real-world ML workflow:

- Three XML datasets (`df_item.xml`, `df_product.xml`, `df_outlet.xml`) are first imported into a MySQL database.
- Python connects to MySQL, retrieves the data, and performs feature engineering.
- Multiple regression models are trained and evaluated using Scikit‑Learn.
- The best model is saved as a pickle file and integrated into a user‑friendly Streamlit web app.
- Users can enter product and outlet details to get an instant sales prediction.

---

## 🏗️ Project Architecture / Workflow
