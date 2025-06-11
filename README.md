# Lab4---Tidying-Cleaning-Imputation-and-Outlier-Detection

The repository contains the entire code for the Lab4 - Tidying, Cleaning, Imputation, and Outlier Detection.

# Approach

- Performed Tidying data with melt()
- Handled missing data using SimpleImputer
- Implemented Outlier detection and removal with Z-Score and IQR
- Visualized data through boxplots and scatterplots
- Worked on three datasets : `Billboard dataset`, `Cars Dataset`, `Diabetes Dataset (load_diabetes)`

### 2. Billboard Dataset

- Cleansed weekly rank columns with melt().
- Extracted the week numbers with regex.
- Computed actual ranking dates with date.entered + timedelta which is the offset.
- Dropped null values and renamed columns.

### 3. Cars Dataset

- Omitted metadata row and converted numeric columns.
- Handled missing values with SimpleImputer (median strategy).
- Removed duplicate values from the dataset.

### 4. Diabetes Dataset (load_diabetes)

- Loaded in-built dataset from sklearn.
- Displayed features via boxplot and scatterplot
- Applied Z-Score and IQR filtering to eliminate outliers

---

## How to Run

1. Clone the repository:

   git clone https://github.com/theRedeemer997/Lab4---Tidying-Cleaning-Imputation-and-Outlier-Detection.git

2. Create a virtual environment using

   ```bash
   python3 -m venv .venv

   ```

3. Activate the virtual environment using

   ```bash
       source ./.venv/Scripts/activate
   ```

4. Install dependencies using the following
   ```bash
   pip install -r requirements.txt
   ```

## References

- week5Lab.ipynb notebook from week5 resource of eConestoga.
