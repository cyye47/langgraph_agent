This exercise uses langgraph to first identify the right file containing pubmed abstracts with LLM. A conditional edge was added to determine if the file contains pubmed abstract content and if the abstract contain patient case studies. Refer to the detailed graph below.

Then use LLM to filter only abstracts containing certain keywords (e.g. breast cancer), and use the PMID to retrieve the pubmed file via URL and identify the drug substances used in the study (via RN tag in pubmed file format).

Then use BioBERT model to predict if the drug substance is closely associated with the keywords.

![graph](https://github.com/cyye47/langgraph_agent/blob/main/image.png)
