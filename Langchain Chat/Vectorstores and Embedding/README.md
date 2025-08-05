# Vectorstores and Embeddings

This is used for easy access of the split chunks. Embedding vector captures content/meaning. Text with similar content will have similar vectors.
These embeddings of the splits will be stores in vectorstores so they can be retrieved later on.

This will become useful when we're trying to find documents for a question at hand. We can then take a question at hand, create an embedding and do comparisons to all the different vectors in the vectorstore and pick the n-most similar. Then take the n-most similar chunks along with the question and pass them to an LLM and get back an answer.

<img width="871" height="796" alt="image" src="https://github.com/user-attachments/assets/12a45e2a-5535-4d1a-ae3c-c851ed56a594" />
