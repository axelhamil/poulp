# 🐙 Poulp

CLI tool for managing databases in shared containers across multiple projects.

## The Problem

Tired of having one container per project because of docker-compose? Poulp lets you share database containers across multiple projects, making resource management more efficient.

## How It Works

Multiple projects can use the same PostgreSQL container, each with:
- Their own dedicated database
- Separate PostgreSQL users for proper isolation
- Clean separation between projects

**For development environments only.**

## Status

🚧 **Currently in development**

## Tech Stack (Planned)

- **TypeScript** - For type safety and developer experience
- **Clean Architecture** - Keeping concerns separated
- **Domain-Driven Design (DDD)** - Modeling the problem domain properly
- **Test-Driven Development (TDD)** - Maybe, if I stick to it this time 😅

## What It Will Do

- Manage shared database containers
- Create isolated databases and users per project
- Simplify development environment setup
- Reduce resource usage compared to per-project containers

---

*Work in progress - ideas welcome!*
