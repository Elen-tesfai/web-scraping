# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

This repository contains a project focused on web scraping and natural language processing (NLP) using Python libraries such as Requests, BeautifulSoup, and spaCy. The goal is to extract article content from a web page, analyze text through token and lemma frequency, and visualize sentence scoring with histograms.

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Contents

- Jupyter Notebook with completed tasks and code
- Scraped article HTML/text files stored separately
- Visualizations of sentence scores based on tokens and lemmas

## Instructions

- Run the notebook sequentially to reproduce results
- All scraped data files are included for reproducibility
- Make sure required packages (`requests`, `beautifulsoup4`, `spacy`, `matplotlib`) are installed

## Setup (Optional)

To run the notebook smoothly, install the required Python packages:

```bash
pip install beautifulsoup4 html5lib ipykernel jupyterlab matplotlib requests spacy spacytextblob
Also, download the spaCy language model used in this project:

```bash
python -m spacy download en_core_web_sm
```
## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

**Author:** Elen Tesfai  
**GitHub Repository:** [https://github.com/Elen-tesfai/web-scraping](https://github.com/Elen-tesfai/web-scraping)