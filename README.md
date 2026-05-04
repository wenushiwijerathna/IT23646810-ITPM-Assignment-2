# IT23646810-ITPM-Assignment-2
# 🧪 Singlish to Sinhala Translator - Test Automation (Playwright)

## 📌 Project Overview

This project automates testing of a **Singlish to Sinhala translator web application** using **Playwright (Python)**.

The script reads test cases from an Excel file, inputs Singlish text into the translator UI, captures the Sinhala output, and compares it with expected results.

---

## 🎯 Objectives

* Automate execution of test cases
* Validate translation accuracy
* Identify failures in the translator
* Save results back into Excel

---

## 🛠️ Technologies Used

* Python
* Playwright
* OpenPyXL
* Excel (.xlsx)

---

## 📂 Project Structure

```
project-root/
│
├── test_automation/
│   ├── test_script.py
│   ├── Assignment 1 - Test cases.xlsx
│   ├── IT23388802 github link.txt
├── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Install Python

Python 3.10+ is installed.

Check:

```bash
python --version
```

---

### 2️⃣ Install Dependencies

```bash
pip install playwright openpyxl
```

---

### 3️⃣ Install Playwright Browsers

```bash
playwright install
```

---

## ▶️ How to Run the Script

Navigate to your project folder:

```bash
cd test_automation
```

Run:

```bash
python test_script.py
```

---

## 📊 Excel File Requirements

Your Excel file must include these columns:

| Column Name     | Description                  |
| --------------- | ---------------------------- |
| Input           | Singlish text                |
| Expected Output | Expected Sinhala translation |
| Actual Output   | (Auto-filled by script)      |
| Status          | FAIL                        |

---

## 🔍 How It Works

1. Opens the translator website
2. Finds input and output text areas
3. Enters Singlish input
4. Clicks **Transliterate** button
5. Captures Sinhala output
6. Compares with expected result
7. Updates Excel file

---

## 🌐 Tested Website

* https://www.pixelssuite.com/chat-translator

---

## 📌 Output

After execution:

* **Actual Output** column is filled
* **Status** column shows:

  
  * ❌ FAIL → Incorrect translation
  

---

## ⚠️ Notes

* Keep internet connection stable
* Do not close browser during execution
* Ensure Excel file is closed before running script

---


## 👨‍💻 Author

wenushi wijerathna

