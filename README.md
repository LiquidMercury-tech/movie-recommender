\# Movie Recommender System



\&gt; \*\*Status:\*\* Work in progress. This is my first data science project — 

\&gt; I'm actively improving it based on feedback. 



\## Current Approach

\- Content-based filtering using CountVectorizer + cosine similarity

\- Dataset: TMDB 10,000 movies

\- Simple genre + overview text matching



\## Known Limitations (I'm Fixing These)



\- \[ ] Using CountVectorizer instead of TF-IDF

\- \[ ] No evaluation metrics (precision@k, etc.)

\- \[ ] No API — notebook-only

\- \[ ] No fuzzy title matching

\- \[ ] Missing data not handled gracefully



\## Quick Start

```bash

pip install -r requirements.txt

jupyter notebook notebooks/01\_initial\_exploration.ipynb

