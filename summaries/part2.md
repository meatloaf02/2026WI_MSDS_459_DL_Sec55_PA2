# Knowledge Graphs — Week 2

## Summary

The scale, complexity, and variability of modern web content have made data
collection for knowledge graphs increasingly challenging. Simple web crawlers
are no longer sufficient, leading to the adoption of focused web crawler
designs. These crawlers consider domain specificity, website link structures,
content usability, and terms of service to reduce noise and improve relevance.

Focused crawlers fall into three categories: best-first crawlers that prioritize
URLs using TF-IDF scores, semantic crawlers that leverage ontologies to identify
similar content, and learning crawlers that adapt using training sets and user
preferences.

Information extraction (IE) from web pages presents additional challenges due to
noise, layered structures, and inconsistent formats. Wrappers are commonly used
to extract data by exploiting HTML structure, though they often require manual
construction tailored to specific domains. These wrappers may be supervised,
semi-supervised, or unsupervised.

Structured data also exists in the deep web, such as e-commerce platforms and
government databases, as well as in tabular formats. Extracting tabular data
remains difficult due to inconsistent table structures, and research in this
area is ongoing.

## References

- Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. 2021. *Knowledge Graphs:
  Fundamentals, Techniques, and Applications*. Cambridge, MA: MIT Press.

- UncleCode. 2024. *Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper*
  [Computer software]. GitHub.  
  https://github.com/unclecode/crawl4ai
