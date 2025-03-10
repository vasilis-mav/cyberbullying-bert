## Introduction
This project focuses on detecting cyberbullying in tweets using a BERT-based model. The dataset consists of labeled tweets categorized as cyberbullying (based on religion, age, ethnicity, etc.) or non-cyberbullying.
The project was done as part of my undergraduate thesis.

## Dataset and Preprocessing
The dataset was preprocessed to improve model performance, including the following steps:
- Stemming – Reducing words to their root form.
- Contraction Expansion – Expanding shortened words (e.g., "don't" → "do not").
- Stopword Removal – Removing common words that do not contribute to meaning.
- Hashtag, Emoji & Link Removal – Cleaning unnecessary elements from tweets.
- Length Filtering – Removing tweets that are too short or too long.
