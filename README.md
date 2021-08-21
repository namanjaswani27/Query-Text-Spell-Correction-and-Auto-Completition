# Query-Text-Spell-Correction-and-Auto-Completition

# Task
Given any query (text input) the model will correct any spellings and will predict the next few words for the query. This can be used to improve user experience on any online searching platforms, especially on e-commerce websites.

# Methods Overview:
- Training:  Trained two separate seq-2-seq models, each with Bahdanau’s Additive Attention.
- Inference: Query text passed through one seq-2-seq model and its spell_corrected output is passed through another seq-2-seq model for auto-completion.

## Dataset
DataSet: Top 20 books from “Project Gutenberg” [dataset](https://www.gutenberg.org)

# Sample Results
![alt text](https://github.com/namanjaswani27/Query-Text-Spell-Correction-and-Auto-Completition/blob/main/sample_results.png?raw=true)








