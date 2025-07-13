# Let Me Ask AI

A modern Q&A platform built with AI capabilities. Developed by Mateus Holanda.

## Tech Stack

### Backend
- [Fastify](https://fastify.io/) - Fast and low overhead web framework
- [DrizzleORM](https://orm.drizzle.team/) - TypeScript ORM
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Zod](https://zod.dev/) - TypeScript-first schema validation
- [TypeScript](https://www.typescriptlang.org/) - Programming language

### Frontend
- [React](https://react.dev/) - UI library
- [Vite](https://vitejs.dev/) - Build tool and development server
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework
- [React Query](https://tanstack.com/query/latest) - Data fetching and state management
- [React Router](https://reactrouter.com/) - Client-side routing

## Project Structure
```
/server - Backend API
/web    - Frontend application
```

## Getting Started

### Prerequisites
- Node.js 18+
- Docker and Docker Compose
- Yarn package manager

### Setup

1. Clone the repository
```bash
git clone <repository-url>
cd let-me-ask-ai
```

2. Backend Setup
```bash
cd server
yarn install
docker-compose up -d # Starts PostgreSQL database
yarn db:seed # Seeds initial data
yarn dev # Starts development server
```

3. Frontend Setup
```bash
cd web
yarn install
yarn dev # Starts development server
```

The application should now be running at:
- Frontend: http://localhost:5173
- Backend: http://localhost:3333

## Project Patterns
- REST API architecture
- TypeScript for type safety
- Component-based UI architecture
- Environment-based configuration
- Database migrations with DrizzleORM 