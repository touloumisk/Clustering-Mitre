# Clustering-Mitre
v1.0
+ preprocesses all mitre corpus
  - words are lemmatized
  - stopwords are removed
  - 50 most frequent mitre words are removed
  - punctuation is removed
+ models is created by clustering the following fields
  - name
  - description
  - detection method
+ clusters and their respective ids are returned 
