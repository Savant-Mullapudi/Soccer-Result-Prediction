This project aims to predict soccer match results using data scraping, machine learning, and data visualization techniques. Below are the steps to run the project successfully:

### 1. start_scraping_data.ipynb

- This file extracts data from the source page [Premier League Stats]     
(https://fbref.com/en/comps/9/2023-2024/2023-2024-Premier-League-Stats).
- The data is extracted from the 'stats_table' HTML class, focusing on hyperlinks containing '/squads/' in their href attribute.
- Requirements: Ensure you have installed pandas and BeautifulSoup libraries.
- Execution: Run the notebook. It automatically fetches the data based on the current HTML structure of the webpage.
- Data Storage: The extracted data for each year is stored in a CSV file. To avoid redundant executions, all acquired data is merged and stored in `final_dataset.csv`.

### 2. start_predicting_data.ipynb

- This notebook utilizes `final_dataset.csv` for prediction.
- Requirements: Place `final_dataset.csv` in the same directory as this notebook.
- Libraries: Ensure you have installed pandas, Random Forest Classifier, and CatBoost for machine learning purposes.
- Execution: Run the notebook for prediction using machine learning algorithms.

### 3. start_visualizing_data.ipynb

- This file employs `final_dataset.csv` for data visualization.
- Requirements: Keep `final_dataset.csv` in the same directory.
- Modules: Ensure all necessary modules are imported.
- Execution: Run the notebook to visualize the data as per the requirements.

Ensure all necessary files are present in the same directory and follow the instructions provided within each notebook for successful execution in jupyter notebook.
