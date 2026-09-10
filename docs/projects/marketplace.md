# Marketplace

## Full-Stack Marketplace Platform

A marketplace application developed as two connected components: a **Next.js web application** and an **Express API** backed by **Supabase**.

The project demonstrates my approach to separating frontend concerns from backend services while building functionality around products, sellers, authentication, images and commerce workflows.

### Architecture

```text
Next.js Web App
       |
       | HTTP / API
       v
Express 5 API
       |
       +---- Supabase Auth
       +---- PostgreSQL
       +---- Supabase Storage
```

### Technology

- **Frontend:** Next.js, React, TypeScript
- **Backend:** Node.js, Express 5
- **Database:** PostgreSQL through Supabase
- **Authentication:** Supabase Auth
- **Storage:** Supabase Storage
- **Development:** Docker, Supabase CLI, npm
- **Testing:** Vitest, Supertest

### Key functionality

- Product discovery, search, filtering, sorting and pagination
- Seller-owned inventory management
- Product creation, editing and deletion
- Product image management
- Authenticated-user endpoints
- Seller access control
- API health checks
- Local Supabase development environment
- Automated tests and smoke/acceptance scripts

### Engineering approach

The API is organised into distinct layers including **routes, controllers, middleware, HTTP handling, configuration and error handling**. This keeps request routing separate from application logic and makes the backend easier to extend.

The project also uses server-only privileged credentials rather than exposing them to the browser.

### Repositories

[Marketplace Web](https://github.com/MakomaneTau/marketplace-web){ .md-button }
[Marketplace API](https://github.com/MakomaneTau/marketplace-api){ .md-button }

## Why this project matters

Marketplace is one of my strongest demonstrations of **backend and full-stack engineering** because it combines application architecture, authentication, database operations, storage, API design, testing and local infrastructure in one system.
