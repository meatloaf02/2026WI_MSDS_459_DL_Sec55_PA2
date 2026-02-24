# pgvector

## Summary

pgvector is a PostgreSQL extension that enables semantic search by storing,
indexing, and querying data as high-dimensional vectors. These vector
representations allow AI systems to capture contextual similarity rather than
relying solely on keyword matching, making retrieval more effective for many
machine learning and AI-driven applications.

A key benefit of pgvector is its seamless integration with existing PostgreSQL
databases, enabling unified queries over both structured and unstructured data.
It is also open source and freely available, making it accessible for academic
and experimental projects.

However, pgvector inherits several limitations common to vector-based systems.
It is subject to the “curse of dimensionality,” which can degrade performance as
dataset size and vector dimensionality increase. Indexing vectors can be
memory-intensive, posing challenges for users with limited local hardware
compared to dedicated vector databases such as Weaviate. Additionally, scaling
pgvector to production-grade workloads can be difficult without significant
engineering effort.

## References

- Google. 2026. “What Is pgvector?”
  https://cloud.google.com/discover/what-is-pgvector

- Jacobs, Alex. 2025. “The Case Against pgvector.” Alex Jacobs (blog), October 29,
  2025. https://alex-jacobs.com/posts/the-case-against-pgvector/

- Weaviate, B.V. 2026. “The AI Open Source Database.”
  https://weaviate.io/platform

- Wikimedia Foundation. 2025. “Curse of Dimensionality.” Last edited October 1,
  2025. https://en.wikipedia.org/wiki/Curse_of_dimensionality
