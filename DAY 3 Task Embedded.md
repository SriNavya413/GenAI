### What is an Embedding?

An embedding is a list of numbers that represents the meaning of text, images, audio, or video.

Similar meaning → numbers are close together.

Where Are Embeddings Used?

Chatbots (RAG systems)

Semantic search

Image and video search

Recommendation systems

### Types of Embeddings

Text → Text embedding models

Image → Vision embeddings (CLIP, ViT)

Video → Frame-based image embeddings

Audio → Audio embeddings (optional)

### Embedding Dimensions

Dimension = number of values in the vector

#### Example: 
[0.2, 0.8, -0.3] → 3 dimensions

More dimensions → better meaning, more cost

### How Embeddings Are Used

Image: 1 image → 1 embedding

Video: Split into frames → each frame → embedding + timestamp

### Storage

Embeddings are stored in a vector database for fast similarity search.

Examples: Pinecone, FAISS, Milvus, Weaviate

### Simple Example Flow

Query: “Show scenes where a person is holding a phone”

Convert query → embedding

Search similar embeddings

Return matching images/video frames

### One-Line Summary

Embeddings turn data into numbers so AI can understand and search by meaning.
