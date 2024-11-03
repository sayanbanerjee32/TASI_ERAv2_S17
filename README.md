# Basic Transformer

## Objective

1. Write the model.py file and then train the model such that it reaches a loss of 3.5 or less in as many epochs as you want. 

## Dataset - opus_books

- The dataset is sources from https://huggingface.co/datasets/Helsinki-NLP/opus_books
- This is a collection of copyright free books aligned by Andras Farkas, which are available from http://www.farkastranslations.com/bilingual_books.php
- The dataset supports 16 different languages.
- The dataset is setup as translation between 2 languages. e.g. for English to Italian `{ "en": "\"Jane, I don't like cavillers or questioners; besides, there is something truly forbidding in a child taking up her elders in that manner.", "it": "— Jane, non mi piace di essere interrogata. Sta male, del resto, che una bimba tratti così i suoi superiori." }`
- This experiment uses only the English - Italian pair of sentences, which contains around 32k rows.


## Result
Achieved loss of 3.4 after 11 epochs
