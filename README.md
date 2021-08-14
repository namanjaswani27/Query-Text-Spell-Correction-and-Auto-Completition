# Query-Text-Spell-Correction-and-Auto-Completition

# Task
Given any query (text input) the model will correct any spellings and will predict the next few words for the query. This can be used to improve user experience on any online searching platforms, especially on e-commerce websites.

# Methods Overview:
- Training:  Trained two separate seq-2-seq models, each with Bahdanau’s Additive Attention.
- Inference: Query text passed through one seq-2-seq model and its spell_corrected output is passed through another seq-2-seq model for auto-completion.

## Dataset
DataSet: Top 20 books from “Project Gutenberg” [dataset](https://www.gutenberg.org)

# Sample Results
<img width="397" alt="image" src="https://user-images.githubusercontent.com/60771226/129457137-576862a3-11c5-4355-b3bf-1e69b069f7ae.png">
<img width="463" alt="image" src="https://user-images.githubusercontent.com/60771226/129457142-6f67d5b5-bedc-4636-b238-ebd1696a1260.png">
<img width="389" alt="image" src="https://user-images.githubusercontent.com/60771226/129457145-a1fcc14b-8166-4c75-a570-b3425fb2428d.png">
<img width="376" alt="image" src="https://user-images.githubusercontent.com/60771226/129457146-6da24423-d66d-44e1-8318-182c8e3dace4.png">







