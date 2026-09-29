# Lab 1 - Modern Database Environment

PostgreSQL 18 lab environment built natively on Windows (pgAdmin 4 + DBeaver), covering database/table creation, data insert/query, and export/import.

## Files

- `lab1_university.sql` - full SQL script (schema + sample data + queries)

## How to restore

    createdb -U postgres lab1_university
    psql -U postgres -d lab1_university -f lab1_university.sql