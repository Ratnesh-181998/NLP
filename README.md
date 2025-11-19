The user searches on GeM portal by entering the “search string” or “search query” . This “search string” or “search query” is directed to 
NLP Engine on Azure Cloud that classifies the “search query” in appropriate category and the result (whether it lies in specified count of 
categories or others) is returned to Search API for Solr to display relevant products on GeM portal.
Step 1: Collection of latest catalogue data and latest active categories list. 
Step 2: Pick up categories to scale up the model on the based of products. (from list of categories provided by GeM) 
Step 3: Categories should have at least 50 products.

![NLP Architecture Diagram](https://github.com/user-attachments/assets/e725ab74-70e6-406e-84c9-769dfce8818c)
