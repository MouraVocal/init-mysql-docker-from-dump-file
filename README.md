# Docker example to initialize Mysql with database and dump file.

## How to use

- Clone this repository
- Put your dump file inside `dump` folder
- Change the dump file name in `Dockerfile` or rename the dump file to `dump.sql`
- Open your terminal and run:
  ```bash
  docker-compose up
  ```
- If you change any file and want to rebuild, run:
  ```bash
  docker-compose up --build
  ```

## Persisting database changes

- From now on there should be a dir `bd` that will persist changes to the database.
