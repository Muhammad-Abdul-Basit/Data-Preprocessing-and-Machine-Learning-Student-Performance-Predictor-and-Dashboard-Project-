Phase 2 – Group ID (F25PROJECTC9A7B)
Data Preprocessing and Machine Learning Models (Jupyter Notebook)

This project covers Phase 2 of the student performance analysis work. All data preprocessing
and machine learning tasks are completed using a Jupyter Notebook.

IMPORTANT NOTE ABOUT CSV FILES:

The notebook works directly with a CSV file and updates it during execution. These updates
include tasks such as filling missing values, normalizing scores, calculating total scores,
assigning grades, and encoding categorical variables.

Because the dataset is modified during execution, running the notebook multiple times on the
same CSV file may cause the data to be processed more than once, which could lead to
unexpected or incorrect results.

BACKUP OF RAW DATA:

To avoid this issue, a file named "backupfile.zip" is included with the project. This ZIP file
contains the original raw CSV dataset.

If you need to run the notebook again from the beginning, please follow these steps:
1. Extract the raw CSV file from backupfile.zip
2. Replace the processed CSV file with the raw one
3. Run the Jupyter Notebook again

This ensures that all preprocessing steps always start from clean, original data.

RUNNING THE NOTEBOOK:

- To run the notebook from start to finish in the correct order, it is recommended to use the
  “Run All” option available in the Jupyter Notebook menu.
- If you only want to run a specific step, you can execute individual cells by selecting
  the cell and clicking the Run button.

Using “Run All” is recommended when executing the notebook for the first time to ensure that
all steps are completed in the proper sequence.

NOTEBOOK INFORMATION:

- This project is fully implemented in a Jupyter Notebook (.ipynb file)
- No external Python scripts are required
- Each code cell includes a short explanation using Markdown for better understanding

SUMMARY:

- The notebook updates the CSV file during execution
- A backup of the original data is provided for safe re-runs
- The notebook supports both full execution (Run All) and step-by-step execution

Please make sure the raw dataset is restored from backupfile.zip before re-running the notebook
from the beginning.
