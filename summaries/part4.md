# ParadeDB

## Summary

ParadeDB is a PostgreSQL extension that brings high-performance, “Elasticsearch-
quality” search capabilities directly into Postgres without requiring an
external search engine or ETL pipeline. This reduces architectural complexity
while preserving the benefits of advanced search and analytics.

One major advantage is deployment flexibility: ParadeDB can be run as a Docker
image or installed as an extension within an existing self-hosted PostgreSQL
instance. It supports both fast semantic search and BM25 ranking (a widely used
TF-IDF–based algorithm), and it is fully compatible with the pgvector extension
for vector-based retrieval.

For many use cases, the free version of ParadeDB provides nearly all of the
functionality available in its paid offerings, making it attractive for
experimental or academic projects.

However, there are some limitations. The free tier does not include automated
backups, which may be acceptable for coursework but would be a concern in
production. ParadeDB also does not currently support popular AI frameworks such
as LangChain, as it is primarily designed as a search engine rather than a
complete AI stack. Finally, because it relies on PostgreSQL hooks, compatibility
issues can arise with certain Postgres configurations or extensions.

## References

- Elasticsearch B.V. 2026. “The Open-Source Platform That Powers Search,
  Observability, Security, and More.”
  https://www.elastic.co/elasticsearch

- ParadeDB. 2026. “Simple, Elastic-Quality Search for Postgres.”
  https://docs.paradedb.com/welcome/introduction

- Wikimedia Foundation. 2026. “Okapi BM25.” Last modified December 30, 2025.
  https://en.wikipedia.org/wiki/Okapi_BM25
