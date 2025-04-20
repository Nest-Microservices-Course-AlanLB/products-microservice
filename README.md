# NestJS - REST API Products Microservice

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

## About the project

This is a RESTful API built using [NestJS](https://nestjs.com/), notes of the
course of [Nest microservices](https://cursos.devtalles.com/courses/nestjs-microservicios).
By Fernando Herrera. The project follows NestJS best practices, including the
use of controllers, services, DTOs, and pipes. It connects to a **SQLite**
database.

## Features

- RESTful API structure
- **NestJS** controllers, services, DTOs, and pipes
- **SQLite** database integration
- CRUD endpoints for managing data

## Prerequisites

Before running the project, make sure you have the following installed:

- **[Node.js](https://nodejs.org/)** (Recommended version: latest LTS)
- **[Nest CLI](https://docs.nestjs.com/cli/overview)** (Globally installed CLI for NestJS)

```sh
npm install -g @nestjs/cli
```

## Installation

Clone this repository and install dependencies:

```sh
git clone [repository_name]
cd [repository_name]
npm install
```

## Running the project in development env

### 1. Configure ENV Variables

Clone the file `.env.template` and change the name to `.env` and configure
variables

### 2. Start the NestJS server

Run the following command to start the development server:

```sh
npm run start:dev
```

### 3. Test the API

Once the server is running, you can test the API endpoints using tools like
**Postman**, **cURL**, or directly in your browser.

### 4. API URL

By default, the API runs on `http://localhost:3000/api/[url_to_test]`.

## Tech Stack

- **NestJS** - Framework for scalable Node.js applications
- **SQLite** - SQL database
- **Prisma** - ORM
