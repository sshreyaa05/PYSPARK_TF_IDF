### PySpark Text Preprocessing Project Using TF-IDF
#### Objective:
The project demonstrates text preprocessing using PySpark and TF-IDF to process a list of 5 sentences. The goal was to tokenize the text, remove stop words, compute Term Frequency (TF) with HashingTF, and apply Inverse Document Frequency (IDF) to get the TF-IDF values.
### 1. Data Creation:
A list of 5 sample sentences was created and indexed from 0 to 4.
### 2. Tokenization:
Tokenization split each sentence into words (tokens) using PySpark’s Tokenizer.
### 3. Stop Word Removal:
Applied StopWordsRemover to eliminate common stop words from the tokenized data.
### 4. Term Frequency (TF) with HashingTF:
HashingTF was used to calculate Term Frequency (TF), creating a frequency vector for each sentence.
### 5. Inverse Document Frequency (IDF):
Applied IDF to weigh the terms based on their importance across the dataset.
### 6. TF-IDF Calculation:
Multiplied TF and IDF to generate the final TF-IDF values, representing the importance of each word in the sentences.
