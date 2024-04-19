Data downloaded 5th of april

<br><br>

## Workflow pipeline:
- preliminar analysis on corpus (length, time, activity)
- data cleaning (removing outliers, selecting only text and index)
- merge and shuffle data
- manual labelling of benchmark following guidelines
- LLM prompt engineering with sBert

<br>

# Content

- `data`: raw data scraped from a forum and telegram groups

- `data_cleaned`: data with only text and original id
    - `all_cleaned.csv`: file with merged data and a label with the source

- `prelim_alaysis.ipynb`: notebook with basic anlalysis of the uncleaned data

- `data_cleaning.ipynb`: notebook used to clean data

- `merge_data.ipynb`: notebook used to merge data and shuffle it

- `embeddings_reduction.ipynb`: notebook with embeddings creation with sentence Bert, reduction and visualization of data

