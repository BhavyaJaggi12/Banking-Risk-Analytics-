# Banking Risk Analytics Platform

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)
![Database](https://img.shields.io/badge/database-MySQL-orange.svg)
![Visualization](httpss://img.shields.io/badge/visualization-Power%20BI-blue)

An end-to-end data analysis project that profiles banking clients to identify key risk indicators. This repository contains the complete workflow, from initial data exploration in Python to a fully interactive risk dashboard in Power BI.

![Final Power BI Risk Analytics Dashboard](https://i.imgur.com/your-dashboard-image.png)

## 📝 Project Overview

This project performs a comprehensive risk analysis on a dataset of **3,000 banking clients**. The primary objective is to identify factors that contribute to a client's risk profile, enabling the bank to make smarter, data-driven lending decisions. The analysis leverages a multi-tool approach to demonstrate a full-cycle data workflow, from raw data processing to business intelligence.

---

## ✨ Key Features & Insights

* **Risk Indicator Identification:** Pinpointed that **loan size** is the most significant predictor of risk, with high-risk clients holding loan balances nearly **200% larger** than low-risk clients.
* **Customer Segmentation:** Revealed that client occupation is a key demographic for segmentation. For example, clients in engineering roles were found to be over **65% more likely** to be in low-risk categories.
* **Risk Concentration Analysis:** The interactive dashboard highlights that the top **5%** of borrowers account for over **15%** of the bank's total loan exposure.
* **Interactive Dashboard:** A user-friendly Power BI dashboard allows non-technical stakeholders to filter and explore the client data to understand risk profiles dynamically.

---

## 🚀 Tech Stack

* **Data Analysis:** Python (Pandas, Seaborn, Matplotlib)
* **Database:** MySQL
* **Business Intelligence & Visualization:** Power BI
* **Development Environment:** Jupyter Notebook

---

## ⚙️ Project Workflow

The project was executed in three distinct phases:

1.  **Discovery & Analysis (Python):** Performed Exploratory Data Analysis (EDA) in a Jupyter Notebook to clean the data, visualize distributions, and calculate the core statistical insights.
2.  **Structuring & Storing (MySQL):** Designed a relational database schema and ingested the cleaned data into a MySQL database to simulate a scalable, real-world production environment.
3.  **Visualization & Communication (Power BI):** Connected Power BI to the MySQL database to build an interactive dashboard, translating complex data into actionable business intelligence.

---

## 🔧 Installation & Setup

To run this project on your local machine, follow these steps:

### 1. Prerequisites

* Python 3.9+
* MySQL Server
* Power BI Desktop

### 2. Clone the Repository

```bash
git clone [https://github.com/BhavyaJaggi12/Banking-Risk-Analytics-.git](https://github.com/BhavyaJaggi12/Banking-Risk-Analytics-.git)
cd Banking-Risk-Analytics-
