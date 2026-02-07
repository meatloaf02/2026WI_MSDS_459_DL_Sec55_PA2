# Knowledge Graphs — Week 3

## Summary

Named Entity Recognition (NER) is a core information extraction technique used to
identify predefined entities within text. It relies on predefined ontologies to
determine which entities are relevant for analysis, making it a critical
component in knowledge graph construction. NER is particularly challenging due
to the ambiguity of natural language, especially when applied beyond English.

NER approaches include supervised, semi-supervised, and unsupervised methods.
Due to the cost of labeled data, unsupervised techniques are commonly used in
practice. Semi-supervised methods offer a balance by leveraging weak supervision.
Long Short-Term Memory (LSTM) networks are a popular unsupervised approach, as
they model long-range dependencies in text through recursive neural network
architectures.

Performance evaluation of information extraction systems often relies on the F1
score, which balances precision and recall.

## References

- Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. 2021. *Knowledge Graphs:
  Fundamentals, Techniques, and Applications*. Cambridge, MA: MIT Press.

- Kundu, Rohit. 2022. *F1 Score in Machine Learning: Intro & Calculation*.  
  https://www.v7labs.com/blog/f1-score-guide

- Olah, Christopher. 2015. *Understanding LSTM Networks*. Colah’s Blog.  
  https://colah.github.io/posts/2015-08-Understanding-LSTMs/
