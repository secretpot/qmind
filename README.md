# QMind
A nl2sql library based on langgraph.

## Requirements
- Python 3.12.3+
- LLM API
- *Milvus 2.5.0+*

## Definitions
### SQL References
Optional metadata stored in Milvus.
Provide some sql references for problems similar to the current problem.
#### Format
Must contain fields: `query`, `sql` and `tags`.
Vector field will be matched the embedding of query.