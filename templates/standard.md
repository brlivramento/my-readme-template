
# Project Name

A short description of the application, its purpose, and the problem it solves.

Additional context about the project, its motivation, or development history.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## Architecture

```mermaid
flowchart LR
    CLIENT["Client"] --> APP["Application"]
    APP --> API["API Layer"]
    API --> DB[("Database")]
    API --> EXT["External Services"]
```

## Features

- User-friendly interface
- Responsive layout
- CRUD operations
- External API integration
- Data persistence
- Error handling and validation

## Prerequisites

Make sure Docker and Docker Compose are installed and the Docker engine is running.

## Run Locally

1. Clone the repository:

```bash
git clone git@github.com:USERNAME/REPOSITORY.git
cd REPOSITORY
```

2. Create your environment file:

```bash
cp .env.example .env
```

3. Configure the required values:

```env
APP_PORT=3000
DATABASE_URL=
API_KEY=
```

4. Start the application:

```bash
docker compose up --build
```

- Application: `http://localhost:3000`

## Project Structure

```text
src/
├── app/
├── components/
├── services/
├── lib/
└── types/
```

## Tests and Build

```bash
npm test
npm run build
```

## Demo

![Application overview](./docs/screenshots/overview.png)

![Application details](./docs/screenshots/details.png)