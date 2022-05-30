This repository contains a method for guided clustering using BERT embeddings. You can create clusters based on provided seed words.

1. Input file should be given as a CSV with documents under the 'text' column.
2. 01_generate_bert_embeddings_for_documents.py will produce embeddings for 
   these documents and output a new CSV file containing document and corresponding embeddings.
3. Use this output CSV in 02_guided_clustering.py. Provide your seed words as input. Output clusters 
   can be saved as a text file. Optimal for short text classification task.