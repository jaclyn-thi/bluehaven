# BlueHaven

BlueHaven is a full-stack education platform for creating classes, sharing course content, and supporting discussion between students and instructors.

Built as a team project for MIT's 6.1040 Software Design course.

**Live Demo:** https://bluehaven-new.vercel.app/

## Features

* Create and join classes
* Publish and organize course content
* Participate in class discussions and Q&A
* Create posts with Markdown support and previews
* Manage user accounts and authentication
* Navigate class-specific content through a responsive single-page interface

## Tech Stack

**Frontend**

* Vue 3
* TypeScript
* Vue Router
* Pinia

**Backend**

* TypeScript
* REST APIs
* MongoDB / MongoDB Atlas
* Mongoose

**Deployment**

* Vercel

## My Contributions

I worked across both the frontend and backend of BlueHaven, with a focus on the platform's discussion and class interaction features.

My contributions included:

* Implementing discussion functionality across the Vue frontend and REST API
* Building interactive UI components for creating and viewing class content
* Working with MongoDB-backed application data
* Debugging integration issues across the frontend and backend
* Contributing to application deployment and testing

## Architecture

BlueHaven is organized as a full-stack TypeScript application.

```text
client/
  components/     Reusable Vue UI components
  views/          Application pages
  router/         Client-side routing
  stores/         Pinia state management

server/
  concepts/       Application domain logic
  routes.ts       REST API routes
  responses.ts    API response formatting
  app.ts          Backend application setup

api/
  index.ts        Vercel server entry point
```

The frontend is a Vue single-page application that communicates with the backend through REST APIs. The backend stores persistent application data in MongoDB.

## Running Locally

Detailed development, MongoDB setup, and deployment instructions are available in [`docs/DEVELOPMENT.md`](docs/DEVELOPMENT.md).

At a high level:

```bash
npm install
npm run dev:server
npm run dev:client
```

A MongoDB connection is required to run the application locally.

## Project Context

BlueHaven was developed as a team project for MIT 6.1040 (Software Design). The repository was originally based on course-provided frontend and backend starter infrastructure and was extended into the complete BlueHaven application.

The original setup and development documentation has been preserved in [`docs/DEVELOPMENT.md`](docs/DEVELOPMENT.md).
