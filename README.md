
# Ideal Function Matching – DLMDSPWP01 Assignment 

This project was developed as part of the **DLMDSPWP01 – Programming with Python** course at IU. It implements a complete pipeline to analyze and map ideal mathematical functions to test data based on least-square deviation.

## Objective

Given:
- A training dataset with 4 target functions
- A set of 50 candidate ideal functions
- A test dataset with `x, y` values

This project:
- Selects the 4 best-fit ideal functions using least-square error
- Maps test points to those functions under a √2 deviation rule
- Stores all results in a local SQLite database
- Visualizes mappings using Bokeh plots

## Project Structure

```
.
├── data/                # Contains CSV datasets and generated database
│   ├── train.csv
│   ├── ideal.csv
│   ├── test.csv
│   └── ideal_functions.db
├── src/                 # Python modules
│   ├── main.py
│   ├── database.py
│   ├── data_processor.py
│   └── visualization.py
├── tests/               # Unit tests with pytest
├── outputs/             # Contains visualization.html (interactive Bokeh plot)
├── requirements.txt
└── README.md
```

## How to Run

1. Clone the repo:
```bash
git clone https://github.com/ganeshlakshmana/IdealFunction-Matching.git
cd IdealFunction-Matching
```

2. Set up environment:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Run the program:
```bash
python src/main.py
```

4. Open results:
- Interactive Plot → `outputs/visualization.html`
- Database → `data/ideal_functions.db` (use DB Browser for SQLite)

## Technologies Used

- **Python 3.8+**
- Pandas, NumPy
- SQLAlchemy (ORM for SQLite)
- Bokeh (interactive visualization)
- Pytest (unit testing)

## Screenshot

> Add a screenshot of your Bokeh HTML here if hosted

## Academic Note

This repository is a demonstration of programming concepts including:
- OOP, exception handling, inheritance
- Data analysis & mapping using least squares
- Database persistence and visualization

## Author details
- Ganesh Lakshmana
- Social: [in/ganesh-lakshmana-71085b224](https://www.linkedin.com/in/ganesh-lakshmana-71085b224/)
- Website: [my portfolio](https://www.ganeshlakshmana.online/)

Originally developed for coursework at IU (International University of Applied Sciences).
---
