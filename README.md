# Book Recommendation Sytem Using Collaborative Filtering
This Algorithm gives most which book you can read according to your book taste. 
Used streamlining to read through Large dataset(5 GB/ 22.8 million records). 

**#File Details-**

**Search_book.ipynb-** unzip 'goodreads_books.json.gz'. In this we can search our books in millions of records. Used TFIDF Vector to transform the data.

**Recommendations.ipynb-** mapped book_id_map.csv with goodreads_interactions.csv, Built a intial recommendations system to give the list of books related to cosine similarity value. Filter out the generic popular books with high ratings, to make it personal for each individual.

**Collaborative_filtering.ipynb-** Used sparse matrix to create User-Book matrix where values are ratings. Again used cosine similarity to find the books.

**Dateset-**  [https://mengtingwan.github.io/data/goodreads.html#datasets
](https://mengtingwan.github.io/data/goodreads.html#datasets)


![Capture](https://github.com/user-attachments/assets/00edcdb3-4e2f-410e-a821-5372a89a502b)
