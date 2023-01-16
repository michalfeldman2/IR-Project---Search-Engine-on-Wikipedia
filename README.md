# IR-Project---Search-Engine-on-Wikipedia
Search engine for English Wikipedia with 6M files.

**Search frontend**
* Search: Search over Wikipedia. The documents relevancy is ranked by the length of the query.
Long query is ranked by BM25 retrieval function and short query is ranked by anchor binary search.

* Search_body: Search over Wikipedia only by the body of the documents.
The documents relevancy is ranked by fast Cosine Similarity score using TF-IDF.

* Search_title: Search over Wikipedia only by the titles of the documents.
The documents relevancy is ranked by binary search.

* Search_anchor: Search over Wikipedia only by the anchor text related to the documents.
The documents relevancy is ranked by binary search.

**Backend wiki**

Three parts:
* Tokenize func and preprocess for the query.
* Load all indices from buckets.
* Functions of search frontend.






