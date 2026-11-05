<img width="1020" height="256" alt="image" src="https://github.com/user-attachments/assets/c3ca24ae-a197-4e01-91ef-76c090b077fe" />

PyRelatio is a simple, working mini relational database in Python, built as a systems
programming project.

PyRelatio implements the core pieces of a relational database (page storage,
buffer management, caching, logging, and transactions) as small, readable
modules. The focus is on how these systems work close to the machine, and on
making each layer fast.

## Features

- Page and file storage
- Buffer pool and caching
- Write-ahead logging
- Transactions

## Status

Early development. The API will change.

## Background

pyrelatio is a Python rewrite of OpusDB, an earlier Clojure implementation. That
version is preserved under the `thesis-v1` tag.

## License

Eclipse Public License 2.0. See [LICENSE](LICENSE).
