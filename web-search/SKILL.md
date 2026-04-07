---
name: web-search
description: Search the web using DuckDuckGo to find accurate and up-to-date information for the user's query.
---

# Web Search

## Instructions

Call the `run_js` tool using `index.html` and a JSON string for `data` with the following exact fields:
- **query**: Required. String. The search query entered by the user. (e.g. "Amazon", "DigitalOcean")

## Important

- Always use this skill when the user asks to search the web, look something up, or needs current information.
- Present the results in a clear, readable format with titles, snippets, and URLs.
- If the abstract is available, summarize it first, then list related topics.
- DO NOT USE: web-search, the name of the skill as the URL parameters
- MAKE SURE TO USE a JSON string {"query": "<the search of the user>"} to do a search
