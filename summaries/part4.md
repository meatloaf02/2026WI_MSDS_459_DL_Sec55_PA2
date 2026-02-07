# Natural Language Processing — Week 1

## Summary

Large Language Models (LLMs) are transformer-based models containing billions to
trillions of parameters. While larger models tend to produce better results,
their effectiveness comes from pattern recognition rather than true intelligence.
Model size alone can also introduce issues such as toxicity and reasoning errors.

Mitigation strategies include scaling, guardrails, grounding models in real-world
facts, and integrating search mechanisms. Scaling may be optimized through
semantic routing, directing prompts to the most suitable model. Guardrails,
however, require constant updates as users find ways around them.

LLMs generate output by predicting the most probable next word based on prior
context and are fine-tuned for specific tasks. Integrating information retrieval
and semantic search can significantly improve factual accuracy, though these
methods are computationally expensive.

As LLM adoption increases, concerns about misuse and ethical implications grow.
While public debate continues, profit-driven incentives often limit the priority
given to risk mitigation.

## References

- Bowdon, Chris. 2025. *How many parameters does GPT-5 have?* R-bloggers.  
  https://www.r-bloggers.com/2025/08/how-many-parameters-does-gpt-5-have/

- Lane, Hobson, and Maria Dyshel. 2025. *Natural Language Processing in Action*
  (2nd ed.). Shelter Island, NY: Manning.

- Meta. 2025. *The Llama 4 herd: The beginning of a new era of natively multimodal
  AI innovation*.  
  https://ai.meta.com/blog/llama-4-multimodal-intelligence/
