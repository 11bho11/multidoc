# Multi Document Analyser via LLMs

Today we test out how LLMs can handle analysing and summarising multiple documents, in which understanding of a document is dependent on the context of its previous documents. 
This is useful in cases where one needs to analyse a sequence of quarterly/annual reports to identify updates and changes over time.

We leverage frameworks such as LangChain and LangGraph to support this task.

Here, I am using Goldman Sachs Private Wealth ISG Outlook from the past three years to identify how its outlook on the market has changed over time. I have scraped its commodities section for simplicity purposes.