# sqlite-vec

[Source on GitHub](https://github.com/asg017/sqlite-vec)

**Category:** Open Source

**Tags:** open-source, sqlite, vector-data, similarity-search

## Description

sqlite-vec is an open-source extension for SQLite that adds vector data types and similarity search, enabling lightweight vector database capabilities. It is designed to be a small and "fast enough" vector search extension that can run anywhere, providing vector search functionality directly in SQLite databases.

## Features

- Adds vector data types to SQLite.
- Enables similarity search (vector search) capabilities within SQLite.
- Designed to be lightweight and portable, running anywhere SQLite runs.
- Successor to `sqlite-vss` with improvements.
- Pre-v1: still under active development and subject to breaking changes.
- Multiple language bindings and integrations:
  - Python (`pip install sqlite-vec`)
  - Node.js (`npm install sqlite-vec`)
  - Ruby (`gem install sqlite-vec`)
  - Go (`go get -u github.com/asg017/sqlite-vec/bindings/go`)
  - Rust (`cargo add sqlite-vec`)
  - Datasette (`datasette install datasette-sqlite-vec`)
  - rqlite (`rqlited -extensions-path=sqlite-vec.tar.gz`)
  - sqlite-utils (`sqlite-utils install sqlite-utils-sqlite-vec`)
- Actively sponsored and supported by Mozilla Builders, Fly.io, Turso, SQLite Cloud, and Shinkai.

## Pricing

sqlite-vec is open-source software and is available for free under open-source licenses.
