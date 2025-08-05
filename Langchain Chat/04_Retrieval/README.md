# Retrieval

In the previous step, basic semantic similarity retrieval was performed but there were some edge cases where this didn't work well. In this step the following more advanced methods are perfromed:

1. Maximum Margial Relevance (MMR)
2. LLM Aided Retrieval
3. Compression

### MMR Algorithm
1. Query the vector store
2. Choose the 'fetch_k' most similar responses
3. Within those responses choose the 'k' most diverse

<img width="777" height="459" alt="image" src="https://github.com/user-attachments/assets/5a00928d-b6b2-477b-94bd-c646ae276f52" />

### LLM Aided Retrieval
1. There are several situations where the query applied to the DB is more than just the question asked
2. One is 'Self-Query' where we can use an LLM to convert the user question into a query

<img width="723" height="493" alt="image" src="https://github.com/user-attachments/assets/4dffb920-6632-4ab9-9cb8-78d913e6dcc4" />

### Compression
Increase the number of results you can put in the context by shrinking the responses into only the relevant information.

<img width="610" height="608" alt="image" src="https://github.com/user-attachments/assets/41ac23bb-d790-4691-b6d9-1fe7479a33cb" />
