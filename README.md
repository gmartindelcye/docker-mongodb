# docker-mongodb
Docker container for MongoDB

Runs version 4.4 as latest version do not run in virtalized environments.

## Instructions

1. Create permanent volumes routes:

    ```bash
    sudo mkdir -p ./mongo/data
    sudo mkdir -p ./mongo/log
    ```

2. Run docker compose:

    ```bash
    docker compose up -d
    ```

### Connection to DB

*Connect*: mongo container    (suggestion, could be anything)

*database*: None (you create the database and collections)

*user*: root

*password*: root