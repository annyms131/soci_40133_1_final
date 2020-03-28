# Final Project for SOCI 40133

My broad research question is if perspectives about social determinants of health have converged and/or diverged and why.

To uncover patterns, I scraped published journal articles via the PubMed API. Given that Public Health articles have descriptive titles and abstracts, I built the corpus consisting of title and abstract along with meta data such as publication year, publisher, and publishing country. After cleaning, the final corpus has 25,188 articles ranging from 1968. 


* data:
  - not as organized; contains original and some clean data
  - containts train, dev, test sets used for BERT
  
* t:
  - subset of the scraped data mainly used for most analyses

* code 
  - step-by-step analyses (EDA, clustering, LDA topic modeling, semantic networks, word embedding, deep neural network classification)
  
