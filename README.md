<img width="300" height="100" alt="pyrelatio-logo" src="https://github.com/user-attachments/assets/f986f309-b757-4436-8518-de4e952df78c" />


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
