# Cloud-based-Search-Engine

<img width="850" alt="design" src="https://github.com/user-attachments/assets/13403a38-7d88-417c-8a5c-1b2d3dedeab5" />


Yahoogle is a Java-based search engine developed without any framework and deployed on the cloud; it was created by myself and four other students as the final course project for the class Internet and Web Systems at the University of Pennsylvania. 

It’s built from a custom HTTP/1.1 server that serves static and dynamic content and supports HTTPS. Its components include a data storage system, analytics engine, web crawler, indexer, and ranking algorithms. The storage system is a distributed key-value store (KVS) that uses consistent hashing for in-memory and persistent data tables. The distributed analytics engine is loosely based on Apache Spark; it processes the large data sets in the KVS, and along with the web crawler and indexer, is used to create the inverted index. The crawler initially crawled around 800K web pages to create a corpus, which was then refined to build the inverted index needed for efficient data retrieval. The PageRank algorithm, term frequency-inverse document frequency (TF-IDF) score, and additional on-page and off-page features are used to rank web pages.

The project code cannot be made public due to course policy, but the search engine can be demoed upon request.
