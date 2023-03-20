# Docker example to initialize Mysql with database and dump file.

## How to use

- Clone this repository
- Create a dir named `dump` on this root repository and put your dump file inside
- Change the dump file name on `Dockerfile` or rename your dump file that should be in `dump` directory to `dump.sql`
- Open your terminal and run:
  ```bash
  docker-compose up
  ```
- If you change any file and want to rebuild, run:
  ```bash
  docker-compose up --build
  ```

## Persisting database changes

- From now on, there should be a dir `bd` that will persist changes to the database.
