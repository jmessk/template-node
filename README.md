# Template for Node.js

This is a template repository for Node.js on Docker and Docker Compose.

## compose.yml

- **user**:
  - User to run the container as, default is `node`
  - `UID` : User ID, default is `1000`
  - `GID` : Group ID, default is `1000`
- **ports**:
  - Ports to expose, default is `3000:3000`

## Getting Started

- To start the container, run:

  ```bash
  docker compose up [-d]
  ```

- to start container for development with bash, run:

  ```bash
  docker compose run --rm dev
  ```
