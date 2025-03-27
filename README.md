This exercise uses langgraph to first identify the right file containing pubmed abstracts with LLM, then use LLM to filter only abstracts containing certain keywords, and then use PMID to retrieve the pubmed file via URL and identify the drug substances used in the study. Output a table with author, journal, PMID and drug substances.
A conditional edge was added to determine if the file contains pubmed abstract content. Refer to the detailed graph below

![graph](https://github.com/cyye47/langgraph_agent/blob/main/image.png)
