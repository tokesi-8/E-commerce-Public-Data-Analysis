# E-Commerce Public Dataset Dashboard ✨

## Project Description

This project is the final project for the **"Belajar Analisis Data dengan Python"** class on Dicoding. The dataset used is the **E-Commerce Public Dataset** from Olist, one of the leading e-commerce platforms in Brazil.

The project covers the complete data analysis workflow, starting from **Data Gathering, Data Assessing, Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization**, and the development of an interactive dashboard using **Streamlit**. In addition, this project applies an advanced analytical technique called **RFM Analysis (Recency, Frequency, Monetary)** to segment customers based on their purchasing behavior.

# Business Questions (SMART)

The analysis focuses on answering the following two main business questions:

* How are customers segmented based on **Recency, Frequency, and Monetary (RFM)** during the 2017–2018 period, and what percentage of the total revenue was contributed by the highest-value customer segment during this period? *(Focus: high-value customer segmentation to improve marketing budget efficiency.)*
* Which **state** generated the highest revenue, and what was the average **delivery time** for each state during 2018? *(Focus: geographic revenue distribution and delivery logistics efficiency.)*

# Directory Structure

* `/data` : Contains the raw dataset files (CSV format) from the E-Commerce Public Dataset used in the analysis.
* `/dashboard` : Contains the main `dashboard.py` Streamlit dashboard script and the cleaned `main_data.csv` dataset used for visualization.
* `notebook.ipynb` : Jupyter Notebook containing step-by-step documentation of the entire data analysis process.
* `requirements.txt` : Contains the Python libraries required to run the project.
* `url.txt` : Contains the access URL for the dashboard.

## Environment Setup - Anaconda

**Create an environment with Python 3.11.0:**

```bash
conda create --name main-ds python=3.11.0
```

**Activate the environment:**

```bash
conda activate main-ds
```

**Install the required libraries:**

```bash
pip install -r requirements.txt
```

## Run Streamlit App

```bash
cd .\dashboard
streamlit run dashboard.py
```
