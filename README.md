# RagChatBot

How to Present This (Summary)

We built a RAG pipeline: Retrieval-Augmented Generation.

Step 1: Load a document (PDF).

Step 2: Split into chunks.

Step 3: Embed chunks into vectors (SentenceTransformers).

Step 4: Store vectors in FAISS.

Step 5: Retrieve top matches for any query.

Step 6: Send retrieved text + query into LLaMA2 via Ollama.

Result: The model gives answers based only on your document → reliable, grounded, and relevant.
