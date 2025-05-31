# Brev.ly

A URL Shortener Application made with React and NodeJS

---

## Overview

**brev.ly** is a full-stack URL shortener application built as part of the FTR (Faculdade de Tecnologia Rocketseat) challenge. It allows users to create, manage, and share shortened URLs with analytics. The project is divided into two main parts:

- **Web (Front-end):** Built with React, Vite and Tailwindcss for a fast, modern user experience.
- **Server (Back-end):** Built with Node.js, using Fastify, PostgreSQL (via Drizzle ORM), integrates with Cloudflare Buckets for storage and documented with OpenAPI/Swagger.

## Features

- Shorten long URLs quickly and easily
- Track usage analytics for each short URL
- User-friendly web interface
- Secure and scalable back-end
- Persistent storage with PostgreSQL
- File/object storage with Cloudflare Buckets

## Project Structure

```
/ (root)
├── web/         # Front-end (React + Vite)
├── server/      # Back-end (NestJS, Drizzle, PostgreSQL)
├── README.md    # Project documentation
└── ...
```

## Documentation

### Web (Front-end)

- You can find the documentation in the `web/README.md` file.

### Server (Back-end)

- You can find the documentation in the `server/README.md` file.
- For API reference, check the OpenAPI/Swagger documentation, available when the server is running at `/api/docs` (or the configured docs route).
