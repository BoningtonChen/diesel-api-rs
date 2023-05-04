# Disel API

## Introduction
A Disel API backend &amp; frontend built by Rust and JS.

## Tips
1. You may need to run `cargo install diesel_cli --no-default-features --features postgres` after forking the project to your device.  \
`--features postgres` is critically important because the database of the project is rely on the PostgresSQL.
2. You may need to run `echo DATABASE_URL=postgres://postgres@localhost/api_dev > .env` to create a `.env` file in the project folder.
3. Run `diesel setup` after you have done the two actions above.
