---
layout: index
---

## 

Course Project (October 2016)

ANTSearch is "document" search engine for a subset of Wikipedia's English language pages. Unlike traditional search engines, it takes whole documents as queries and returns relevant/similar documents as results. It's architecture is based on [1]. Document similarity is computed by representing documents in the Vector Space Model using TFIDF scores and word centrality measures. The similarity metric is enhanced to take into consideration contextually similar words by making use of a Word2Vec NLP model. The search engine sports a web front end with features like similar term word clouds for each of the search results.  


References:

[1] Kim, Wooju and Jang, Heewon and Kim, Hak-Jin and Kim, Donghe. A Document Query Search Using an Extended Centrality with the Word2Vec. In the Proceedings of the 18th Annual International Conference on Electronic Commerce: E-Commerce in Smart Connected World.
