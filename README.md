# Backend Development Exercises

A collection of exercises and course submissions from my backend development studies. Each directory is a separate example, rather than a single application.

## Topics

- Node.js and Express applications
- REST APIs, routing and middleware
- MongoDB and data access
- Sessions, authentication and Passport
- Environment configuration, child processes and logging
- Course submissions and final project

## Repository layout

- `desafio1` to `desafio20` (where present): individual exercises.
- `primera-entrega`, `segunda-entrega`, `tercera-entrega`: course milestones.
- `proyectoFinal`: final course submission.

## Running an exercise

Open the relevant directory, inspect its `package.json` and install its dependencies with `npm ci` when a lockfile is present, or `npm install` otherwise. Use the scripts provided by that exercise.

Where environment templates are included, copy `.env.example` to `.env` in the same directory and supply your own local configuration. Do not reuse credentials from old commits. Some exercises depend on external services and older dependencies.

This is an educational archive. The examples are preserved as learning material and have not been tested as a complete suite.

[BlackCoffeeIA](https://github.com/BlackCoffeeIA)
