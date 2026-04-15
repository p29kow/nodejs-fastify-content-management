# NodeJS Fastify Content Management System

A lightweight, efficient blogging platform built with Node.js, Fastify, and MaterializeCSS. This project demonstrates a modular architecture for managing posts, advertisements, and public-facing views.

## 🚀 Technologies Used

- **Backend:** Node.js
- **Framework:** Fastify (High-performance web framework)
- **Templating Engine:** EJS (Embedded JavaScript)
- **Frontend Framework:** MaterializeCSS (Material Design-based UI)
- **Validation:** Fastify-predictive schema handling (via config-schema.js)

## 📂 Project Structure

| Directory | Description |
|-----------|-------------|
| `ads/` | Management logic for site advertisements |
| `config/` | Configuration files and environment settings |
| `helpers/` | Reusable utility functions for the application |
| `plugins/` | Fastify plugins for modularity (e.g., DB connections, authentication) |
| `public/` | Static assets including CSS, JavaScript, and images |
| `routes/` | API and frontend route definitions (Posts, Admin, etc.) |
| `services/` | Business logic layer to separate concerns from routes |
| `views/` | EJS templates for the frontend UI |

## 🛠️ Installation

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
