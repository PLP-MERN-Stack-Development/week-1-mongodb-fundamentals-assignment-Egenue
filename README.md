# PLP Bookstore – MongoDB Week 1 Assignment

## Setup Instructions

1. Ensure MongoDB is running locally on `localhost:27017`
2. Run:
    ```bash
    npm install mongodb
    node insert_books.js
    ```
3. Use MongoDB Compass or mongosh to run the queries in `queries.js`

## Files

- `insert_books.js`: Inserts 12 books into the `plp_bookstore.books` collection
- `queries.js`: CRUD, advanced queries, aggregation, and indexing

## Notes

- Drops the collection if it exists before inserting
- No authentication required if MongoDB is running with default config
