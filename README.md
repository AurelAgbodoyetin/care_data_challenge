# CARE DATA CHALLENGE



## Project Structure
```
project-root/
│
├── data/
│   ├── CUSTOMERS.XLSX
│   ├── EMPLOYEES.XLSX
│   ├── ITEMS.XLSX
│   ├── ORDERINFO.XLSX
│   └── ORDERS.XLSX
│   
├── notebooks/
│   └── exploration.ipynb
│   
├── requirements.txt
├── README.md
└── main.py
```

## Requirements

* Python 3.x (recommended version)
* Dependencies listed in `requirements.txt`
   ```
   pandas==2.1.1
   numpy==1.23.5
   matplotlib==3.8.0
   seaborn==0.12.2
   calplot==0.1.7.5
   adtk==0.6.2
   scipy==1.11.3
   scikit-learn==1.3.0
   ```

## Installation

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

2. **(Optional) Set up environment:**
   If you prefer using a virtual environment, you can activate it before installing dependencies. For example:
   ```
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

## Running the Core Notebook

1. Open the Jupyter notebook interface:
   ```
   jupyter-notebook
   ```

2. Navigate to the `notebooks` folder within your project directory.

3. Open the `exploration.ipynb` notebook.

4. You can directly run the following command in your terminal to open the notebook:

```bash
jupyter-notebook notebooks/core_notebook.ipynb
```
This will open the Jupyter Notebook in your default web browser.

5. Run the cells in the notebook to execute the code.