---
name: edge-gallery-duckduckgo
description: A skill that allows users to search via DuckDuckGo
metadata:
  homepage: https://kostanye.github.io/edge-gallery-ddg
---



# Edge Gallery DuckDuckGo Skill

## Instructions

To use the Edge Gallery DuckDuckGo skill, format the search queries using main topic keywords rather than full natural language sentences (e.g. use "Paris", "France" or "Cows" instead of "What is the capital of France?"). The skill will utilize the DuckDuckGo search engine to retrieve relevant information and provide you with concise answers or summaries based on the search results.

When calling the skill's execution environment, you must pass the data as a valid JSON string with the following structure:
```json
{
  "query": "<your optimized keyword query here>"
}
```