## Paper_search

Auto-GPT Plugin for Semantic Scholar Search [Semantic Scholar API](https://www.semanticscholar.org/).

## Overview

- Retrieve related papers from [unofficial semantic scholar library](https://github.com/danielnsilva/semanticscholar) via the `search_papers` command

 ![untitled](https://github.com/sokolheavy/Paper_search/assets/36013697/8cad586c-e719-4583-815c-ba35ba242b8e)

## Instructions

- Install the requirements

```bash
pip install -r requirements.txt
```

Add this chunk of code to the `.env` file within AutoGPT:

```
################################################################################
### PAPER SEARCH SETTINGS
################################################################################
SS_SEARCH_YEAR=2022 # limit of year, default: None
SS_SEARCH_LIMIT=100 # limit of kept results (screened by citation), default: 100
SS_SEARCH_FIELDS_OF_STUDY=['NLP'] # limit of search fields of study, default: None
```
