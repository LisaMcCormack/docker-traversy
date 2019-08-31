# Docker Node MongoDB Example

> Simple <a href="https://www.youtube.com/watch?v=hP77Rua1E0c">example</a> of a dockerized Node/Mongo 

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
