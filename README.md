
# Python Function Mapping 📊

A comprehensive Python project developed for the DLMDSPWP01 module at IU. This solution selects ideal functions for a given training dataset based on least-square error, maps test data under a √2 deviation constraint, stores results in a SQLite database, and visualizes the relationships using Bokeh.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Status](https://img.shields.io/badge/status-Tested--and--Working-brightgreen)
![License](https://img.shields.io/badge/license-Academic-lightgrey)

---

## 📌 Summary of Modifications and Features

- ✅ Used **official datasets** provided via tutor ticket (not dummy)
- ✅ Applied **least-square deviation** to select 4 ideal functions from 50
- ✅ Mapped test data points with √2 * max deviation rule
- ✅ Built using **modular OOP** (class-based design)
- ✅ Stored results in **SQLite** using **SQLAlchemy ORM**
- ✅ Created **interactive Bokeh visualizations**
- ✅ Fully **unit tested with pytest**
- ✅ Anti-plagiarism compliant with academic declaration
- ✅ Deployment-ready structure with `requirements.txt` and Git integration

---

## 📁 Folder Structure

```
.
├── data/
│   ├── train.csv
│   ├── ideal.csv
│   ├── test.csv
│   └── ideal_functions.db
├── src/
│   ├── main.py
│   ├── data_processor.py
│   ├── database.py
│   └── visualization.py
├── tests/
│   └── test_all.py
├── outputs/
│   └── visualization.html
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run This Project

```bash
# Clone the repo
git clone https://github.com/ganeshlakshmana/python-function-mapping.git
cd python-function-mapping

# Setup Python environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install all required packages
pip install -r requirements.txt

# Run the application
python src/main.py
```

---

## 🧪 Run Unit Tests

```bash
pytest tests/
```

- Validates correct ideal function selection and test data mapping logic
- Includes mock test data generation

---

## 🔍 Outputs & Verification

- `outputs/visualization.html` → View in browser for interactive plots
- `data/ideal_functions.db` → Open with DB Browser for SQLite to inspect mapped results
- `tests/test_all.py` → Unit tests with `pytest`

---

## 📚 Academic Integrity Note

This project was built and submitted independently as part of coursework for **IU – DLMDSPWP01: Programming with Python**. The solution follows IU's academic integrity guidelines and Turnitin compliance requirements.

---

## 👨‍💻 Author

**Ganesh Lakshmana**  
Matriculation Number: 10241551  
GitHub: [@ganeshlakshmana](https://github.com/ganeshlakshmana)
Linkedin:(https://www.linkedin.com/in/ganesh-lakshmana-71085b224/)

---
