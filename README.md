# MatchMind AI: Intelligent Candidate Discovery Pipeline

An end-to-end Data & AI solution designed to match candidate profiles against target job criteria using an advanced semantic information retrieval framework.

## 🚀 Architecture
1. **Stage 1 (Semantic Filtering):** Uses a Bi-Encoder (`all-MiniLM-L6-v2`) to generate dense vector embeddings of job descriptions and candidate text, filtering down the dataset using rapid Cosine Similarity.
2. **Stage 2 (Business Feature Weighting):** Filters profiles against critical business constraints, penalizing service-firm background patterns and boosting verified product engineering backgrounds alongside platform recency metrics.

## 📊 Outputs
* Generates a fully compiled tracking matrix saved as `submission.xlsx`.
