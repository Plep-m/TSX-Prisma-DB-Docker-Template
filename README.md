# TSX-Prisma-DB Docker Template

The "TSX-Prisma-DB Docker Template" is a minimalist development template that provides a Docker environment for building a REST API with TypeScript, Express, Prisma, and MariaDB. It comes with a pre-configured `docker-compose.yml` file and a sample `Dockerfile` that can be used as a starting point for your project.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/tsx-prisma-db-docker-template.git`
2. Change into the project directory: `cd tsx-prisma-db-docker-template`
3. Build and start the Docker containers: `docker-compose up`

The above commands will start the application in development mode with live reloading. You can now access the REST API at `http://localhost:3000`.

## Project Architecture

The project directory structure is as follows:

```
project/
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── database/
│   ├── index.ts
├── package.json
├── yarn.lock
├── prisma/
│   ├── schema.prisma
```
