# Homework NLP 2023
Code used as part of the NLP course in the Digital Humanities master's program at the École Nationale des Chartes.

The report in pdf format can be viewed [here.](https://nbviewer.org/github/savaij/devoir_TAL/blob/main/latex_report/master_document/master_doc.pdf)

Data downloaded the 5th of april 2024
<br>

# Content

- `data`: raw data scraped from a forum and telegram groups
    - `all_raw.csv`: file with merged text data and a label with the source

<br>

- `data_cleaned`:
    - `all_cleaned.csv`: file with merged data and a label with the source

<br>

- `merge_data.ipynb`: notebook used to merge data and create `all_raw.csv`

<br>

- `data_cleaning.ipynb`: notebook used to clean data (removing NaN and too short and too long texts) and create `all_cleaned.csv`

<br>

- `embeddings_reduction.ipynb`: notebook with embeddings creation with sentence Bert, reduction and visualization of data. <br> 
Note: this notebook has been executed in Google Colab <a target="_blank" href="https://colab.research.google.com/github/savaij/devoir_TAL/blob/main/data_preprocessing/embeddings_reduction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>