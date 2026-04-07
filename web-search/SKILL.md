---
name: web-search
description: Search the web using DuckDuckGo to find accurate and up-to-date information for the user's query.
---

# Web Search

## Instructions

Call the `run_js` tool with the following exact parameters:
- url: should be index.html
- data: A JSON string with the following field:
  - query: String. The search query entered by the user. Ex: {"query": "Who is the french president"}

## Important

- Always use this skill when the user asks to search the web, look something up, or needs current information.
- Present the results in a clear, readable format with titles, snippets, and URLs.
- If the abstract is available, summarize it first, then list related topics.
