# Azure AI Search - Create a Hybrid Search Solution (including vector search)
 [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search) provides secure information retrieval at scale over user-owned content in traditional and generative AI search applications.

Information retrieval is foundational to any app that surfaces text and vectors. Common scenarios include catalog or document search, data exploration, and increasingly chat-style apps over proprietary grounding data. When you create a search service, you work with the following capabilities:
- A search engine for vector search and full text and hybrid search over a search index
- Rich indexing with integrated data chunking and vectorization (preview), lexical analysis for text, and optional AI enrichment for content extraction and transformation
- Rich query syntax for vector queries, text search, hybrid queries, fuzzy search, autocomplete, geo-search and others
- Azure scale, security, and reach
- Azure integration at the data layer, machine learning layer, Azure AI services and Azure OpenAI

## Lab Scenario
In this lab, you will create a hybrid search solution that includes vector search. You will use Azure AI Search to create a search index, and you will use Azure OpenAI to create embeddings for the search index. You will then expose the search index as a REST API.

** Configure pipeline to create a new AI Search that does following:**
1. Get documents from Azure Storage account (container)
2. Chunk documents into smaller pieces
3. Create embeddings using AOAI Ada embedding model 
4. Store embeddings in built-in managed vector store in Azure AI Search
5. Index documents in Azure AI Search
6. Expose the AI Search index as REST API
7. Query the REST API to get search results

You can use the provided test data or bring your own data.

## Lab Implementation
Follow step-by-step instructions provided in the lab guide (AzureAISearch-CreateHybridSearch-with-VectorSearch.pdf) to implement the lab scenario.