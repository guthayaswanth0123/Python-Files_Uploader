# 📁 Multiple File Uploader – Automated Excel to MySQL Import Tool

This project is a simple and efficient **HTML-based multiple file uploader** that allows users to upload **multiple Excel files** at once and automatically store the data into a **MySQL database**.  
It eliminates the need for manual data entry in MySQL Workbench and ensures **speed, accuracy, and time-saving automation**.

---

## 🚀 Features

- 📥 Upload **multiple Excel (.xlsx) or CSV files** together  
- 🔄 Automatically reads and processes each file  
- 🗃️ Creates tables dynamically based on file name  
- 🧹 Cleans and validates data before storing  
- 🛢️ Inserts all rows directly into **MySQL**  
- 🧮 Ensures high accuracy and avoids manual errors  
- ⏳ Saves significant time for large datasets  
- 🌐 Simple HTML interface (easy to use)

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|----------|
| **HTML** | Frontend user interface for file uploads |
| **Python** | Backend processing logic |
| **Pandas** | Reading Excel and CSV data |
| **MySQL** | Database for storing uploaded data |
| **MySQL Connector** | Connecting Python to MySQL |

---

## 📂 Project Structure
excel_uploader/
│── app.py               # Backend script to read and insert Excel data
│── templates/
│   ├── index.html       # Upload page
│   ├── upload.html      # Results page
│── venv/                # Virtual environment (ignored)
│── .gitignore
│── README.md

Setup Instructions
✔ 1. Clone Repository
git clone https://github.com/guthayaswanth0123/Python-Files_Uploader.git
cd Python-Files_Uploader/excel_uploader

✔ 2. Install Dependencies
pip install pandas mysql-connector-python

✔ 3. Configure MySQL Connection
Update these values inside app.py:

host = "localhost"
user = "root"
password = "YOUR_PASSWORD"
database = "YOUR_DATABASE"

✔ 4. Run Backend Script
python app.py

✍️ Author
Gutha Yaswanth
Developer • Data Enthusiast • Automation Builder
-- "Automation is not just about saving time — it's about unlocking human potential for bigger ideas."
Your HTML upload page will handle the file selection.<img width="1919" height="1199" alt="Screenshot 2025-12-11 114610" src="https://github.com/user-attachments/assets/9d0b873b-125e-46fd-b938-526f5a2b511c" />
