# 🛒 E-Commerce ETL Pipeline | CSV to MySQL Automation

![Python](https://img.shields.io/badge/Python-3.x-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![ETL](https://img.shields.io/badge/Project-ETL-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

A fully automated ETL (Extract, Transform, Load) pipeline built using Python and MySQL that imports structured e-commerce CSV datasets into a relational database.

This project demonstrates real-world backend data engineering workflow including dynamic table creation, data cleaning, and automated SQL data insertion.

---

## 🎯 Project Objective

To design and implement an automated system that:

- Extracts structured CSV datasets  
- Cleans and transforms raw data  
- Dynamically creates relational tables  
- Loads processed data into MySQL  
- Handles missing values efficiently  

---

## 🧠 Architecture Flow

CSV Files
↓
Pandas DataFrame
↓
Data Cleaning & Type Detection
↓
Dynamic SQL Table Creation
↓
Bulk Data Insertion
↓
MySQL Database (ecommerce)


📄 View Project Design: `Untitled design.pdf`

---

## 🛠 Tech Stack

- 🐍 Python 3  
- 📊 Pandas  
- 🗄 MySQL Server  
- 🔌 mysql-connector-python  
- 🧾 SQL  

---

## 📂 Dataset Tables Created

| CSV File | MySQL Table |
|----------|------------|
| customers.csv | customers |
| orders.csv | orders |
| sellers.csv | sellers |
| products.csv | products |
| geolocation.csv | geolocation |
| payments.csv | payments |
| order_item.csv | order_item |

---

## ⚙️ Key Features

✔ Automatic SQL table creation  
✔ Dynamic datatype detection (INT, FLOAT, BOOLEAN, DATETIME, TEXT)  
✔ NULL value handling (NaN → SQL NULL)  
✔ Multi-file processing automation  
✔ Secure database connection  
✔ Clean column formatting  

---

## 🔍 Data Engineering Concepts Demonstrated

- ETL Pipeline Development  
- Database Connectivity with Python  
- SQL Automation  
- Data Cleaning & Preprocessing  
- Backend Data Handling  
