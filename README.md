## Table of Contents

- [Key Features](#key-features)
- [Stack](#stack)
- [Setup](#setup)
- [Browser Extensions](#browser-extensions)
- [API](#api)
- [Integrations](#integrations)
- [3rd Party API Packages](#3rd-party-api-packages)
- [Contributing](#contributing)

## Key Features

- Free and open source.
- Custom domain support.
- Custom URLs for shortened links
- Setting password for links.
- Private statistics for shortened URLs.
- View and manage your links.
- RESTful API.

## Stack

- Node (Web server)
- Express (Web server framework)
- Passport (Authentication)
- React (UI library)
- Next (Universal/server-side rendered React)
- Redux (State management)
- styled-components (CSS styling solution library)
- Recharts (Chart library)
- PostgreSQL (database)

## Setup

You need to have [Node.js](https://nodejs.org/), [PostgreSQL](https://www.postgresql.org/) and [Redis](https://redis.io/) installed.

1. Copy `.example.env` to `.env` and fill it properly.
2. Install dependencies: `npm install`.
3. Run for development: `npm run dev`.
4. Run for production: `npm run build` then `npm start`.
