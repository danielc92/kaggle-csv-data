# Csv Data
This repository serves as a backend for the [flask-visualization](https://github.com/danielc92/flask_visualization) web application project. It is essentially a collection of publicly available .csv files, with the intent of being imported using `pandas.read_csv` function from any given web application.

# Before you get started
Required to know how to use `pandas` basic functions such as `read_csv`.

# Setup
**How to obtain this repository:**
```sh
git clone https://github.com/danielc92/kaggle-csv-data.git
```

# Tests
- Calling raw `.csv` links with `pandas` library successfully.

# Usage Example 
```python
url = 'https://raw.githubusercontent.com/danielc92/kaggle-csv-data/master/r-datasets/Arrests.csv'
data = pandas.read_csv(url)
print(data.head())
```

# Contributors
- Daniel Corcoran

# Sources
- The `csv` data in this repo is downloaded from multiple repositories, more detail can be found in the [flask-visualization's](https://github.com/danielc92/flask_visualization) **README.md**
