# DE_project

This project demonstrates a big data migration process using Spark, Flask, and Avro. The project is divided into three parts:

1. Move historic data from CSV files to a new database.
2. Backup data in AVRO format.
3. Restore data from AVRO backups.

The rows of the fact table that do not pass a validation rule are extracted from it and are logged.
## Project Structure

- `data/` - Directory to store CSV files.
- `notebooks/` - Jupyter notebooks for each part of the project.
- `requirements.txt` - List of Python packages required.
- `.gitignore` - Git ignore file.
- `README.md` - Project documentation.

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/big-data-migration.git
    cd big-data-migration
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Navigate to the `notebooks` directory and start Jupyter:
    ```bash
    cd notebooks
    jupyter notebook
    ```

## Notebooks

1. **01_data_loading.ipynb**: Load CSV data, transform, and load into the new database.
2. **02_backup**: Backup the data in AVRO files.
3. **Utilities.ipynb**: Import all the libraries and functions that will be used on the notebooks.

