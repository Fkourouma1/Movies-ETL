# Movies-ETL
Wikipedia has a ton of information about movies, including budgets and box office returns, cast and crew, production and distribution, and so much more. Luckily, one of Britta's coworkers created a script to go through a list of movies on Wikipedia from 1990 to 2018 and extract the data from the sidebar into a JSON. Unfortunately, her coworker can't find the script anymore and just has the JSON file. We'll need to load in the JSON file into a Pandas DataFrame.

## Deliverable 1 
Write an ETL Function to Read Three Data Files
## Deliverable 2 
Extract and Transform the Wikipedia Data
## Deliverable 3 
Extract and Transform the Kaggle data
Deliverable 4 Create the Movie Database
We will extract scraped Wikipedia data stored as JSON and the Kaggle data stored in CSV in the Extract phase. In the Transform phase, we will utilize Python and Pandas in a Jupyter Notebook to explore, document, and perform our data transformation. After the data is transformed into a consistent structure, it's loaded into the PostgreSQL database. Finally, we will create multiple functions to load files, clean the files loaded, merge the cleaned data, and load the merged data to its data target. This function will form a data pipeline that can be easily modified and reused for future ETL projects.

