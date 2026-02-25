# my-learning
my learning on DevOps concepts

Docker: Docker is a containerization platform.
Package applications with all dependencies.
Run them consistently on any server.
Deploy faster.
Scale easily.
Avoid “works on my machine” problems.

Companies use:
Docker for application containers.
Docker Compose for local development.
Docker with CI/CD pipelines.
Docker with Kubernetes for production.


How Companies Actually Use Docker

Imagine a company building:

Backend → Node.js API
Frontend → React app
Database → PostgreSQL
Redis → caching

Instead of installing everything manually, they use:
One container for backend
One container for frontend
One container for PostgreSQL
One container for Redis
Everything runs isolated and clean.

In production:
They build Docker images.
Push them to Docker Hub or private registry.
Deploy on cloud (AWS, Azure, GCP).
Use Kubernetes for scaling.
