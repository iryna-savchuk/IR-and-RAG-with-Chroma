# Advanced Retrieval for AI with Chroma 
(based on materials on deaplearning.ai)

## Overview
To get useful results in Information Retrieval (IR) and Retrieval Augmented Generation (RAG), the retrieved information should match the query and its purpose. Sometimes, queries give similar but off-topic results or distractions. This repo focuses on advanced retrieval techniques to enhance the relevance of obtained information.

## The techniques covered  
- **Query Expansion**:
  - Expanding user queries by including related concepts and keywords to improve IR
  - Utilizing an LLM 
  - Obtaining  a possible answer to the query with LLM, and then including it in the query
- **Cross-encoder reranking**: Reranking retrieval results to select the results most relevant to your query improves your results.
Training and utilizing Embedding Adapters: Adding an adapter layer to reshape embeddings can improve retrieval by emphasizing elements relevant to your application.


## Notes
 - Some warnings pop up when running the notebooks. These are normal and can be ignored.
 - Some operations such as calling an LLM or an operation using generated data return unpredictable results. So, the notebook outputs may differ in different runs.
