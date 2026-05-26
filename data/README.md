# 📂 Data Directory

This folder contains the tourism dataset used for analysis.

## Dataset

- **CSV_1_2_2_.CSV** - Japan International Tourism Data
  - Contains visitor statistics by country
  - Source: Japanese Tourism Bureau
  - Fields: Country/Area, Number of Visitors, Rank

## Usage

The dataset is automatically loaded by the notebook in `notebooks/Japan_Tourism.ipynb`

### File Path
When running locally, ensure the CSV file is placed in the `data/` directory or update the file path in the notebook accordingly.

## Data Preprocessing

The notebook performs the following data cleaning operations:
- Column name standardization
- Removal of comma formatting in numeric values
- Conversion to proper data types
- Handling of missing values
- Continental classification mapping
- ISO country code mapping for visualization

---

*For data access or inquiries, please refer to official Japan Tourism Board statistics.*
