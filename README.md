
# Information Retrieval System

This project implements a simple Information Retrieval (IR) system that demonstrates boolean retrieval operations such as AND, OR, and NOT.

## Contributors
- Abdalelah Taleb

## Overview
The system processes a collection of documents and allows users to query the collection using boolean operators. It generates a term-document incidence matrix to represent the presence or absence of terms in each document. The boolean retrieval process filters documents based on user queries and returns relevant results.

## Components
1. **Document Collection:** It consists of a set of documents represented as strings.
2. **Term Extraction:** The system extracts terms from the document collection and removes duplicates to create a list of unique terms.
3. **Document Representation:** Each document is represented as a list of unique terms.
4. **Term-Document Incidence Matrix:** It represents the presence or absence of terms in each document using binary values (1 for presence, 0 for absence).
5. **Query Processing:** Users can input queries containing boolean operators (AND, OR, NOT). The system filters documents based on these queries.
6. **Boolean Operator Processing:** It applies boolean operators to filter documents based on query terms.

## Usage
1. **Input:** Provide a document collection and a query string containing boolean operators.
2. **Output:** Retrieve documents matching the query string based on boolean operations.

## Example
```python
query = "wink AND drink"
Boolean_retrieval(query, collection)
```
This will retrieve documents containing both "wink" and "drink".

## Future Improvements
- Incorporate more advanced retrieval algorithms such as vector space model or BM25.
- Enhance query processing to support phrase queries or proximity search.
- Improve system efficiency for large document collections.
```

This README provides an overview of the project, its components, usage instructions, and an example. It also suggests future improvements to enhance the system's functionality. Feel free to modify and expand upon this README as needed.
