# Hybrid Index Prototype for SQLite

This project is a prototype implementation of a hybrid indexing structure for SQLite, 
designed to enhance text search capabilities. It combines:

- **Trie indexing** for efficient prefix-based lookups.
- **N-gram inverted indexing** for substring and fuzzy search support.

The hybrid design allows flexible, high-performance querying on text columns in SQLite databases, 
enabling both fast exact matches and approximate text search.

## Features

- Integrated directly into SQLite's virtual machine.
- Supports efficient multi-pattern and partial text matching.
- Experimental design for academic or research purposes.

## Use Cases

- Search engines with partial input support.
- Autocomplete and suggestions in embedded systems.
- Applications requiring fast and fuzzy matching over structured data.

## Status

Research/Prototype phase — not production ready.
