# Natural Language Processing — Week 2

## Summary

For large language models to reason effectively, they must process structured
knowledge derived from text corpora. Extracting entities and relationships from
text enables this knowledge to be stored and queried efficiently, often using
knowledge graphs. These graphs allow LLMs to ground responses and explain
reasoning to users.

Document chunking and sentence segmentation introduce structure into unstructured
text, improving search and extraction accuracy. SpaCy is a widely used Python
library that supports these tasks and includes coreference resolution to
normalize named entities and reduce redundancy.

Relationship extraction relies on dependency and constituency parsing.
Dependency parsing captures grammatical relationships, while constituency
parsing models syntactic structure. Pattern-based and machine learning methods
can be used to extract these relationships into a knowledge graph.

Once populated, knowledge graphs can be queried using languages such as SPARQL,
Cypher, and GraphQL. SPARQL remains a widely adopted open standard for querying
graph-based data.

## References

- Lane, Hobson, and Maria Dyshel. 2025. *Natural Language Processing in Action*
  (2nd ed.). Shelter Island, NY: Manning.

- Kitaev, Nikita. 2021. *Berkeley Neural Parser*. Python Package Index.  
  https://pypi.org/project/benepar/

- W3C. 2013. *SPARQL 1.1 Query Language*.  
  https://www.w3.org/TR/sparql11-query/

- Singh, Taranjeet. 2025. *Natural Language Processing with spaCy in Python*.  
  https://realpython.com/natural-language-processing-spacy-python/
