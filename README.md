# Event Manager App

The Event Manager App is a web application that allows users to browse various events and provides administrators with tools to manage those events. This README provides an overview of the project and instructions for running it locally.

## Problem Statement

You are tasked with developing an **Event Manager App** where users can browse various events. The app should have a login form for Admins. Admins should be able to manage events by creating, updating, and deleting events. Users should have the ability to filter events and sort events by price.

## Features

- **Login Page**: Admins can log in using their credentials, and upon successful login, they are redirected to the Admin Dashboard.

- **Admin Dashboard**: A protected route where admins can manage events. They can create, update, and delete events. Event data is stored in a JSON Server.

- **Events Page**: Users can browse events, filter by category, and sort by price.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [JSON Server](https://github.com/typicode/json-server) installed (for the backend)

### Installation

1. Clone the repository:

- git clone <https://github.com/bhandwalkardarshan/Event-Manager>
- cd event-manager-app

2. Install dependencies:

- npm install

3. Usage

- Start the JSON Server:
    json-server --watch db.json
- Start the development server:
    npm start
- Open the app in your browser:
    http://localhost:3000

### Deployment
- Frontend: [https://frontend-event-management.vercel.app/index.html]
- Backend (JSON Server): [https://backendeventmanagement-production.up.railway.app/]

### Built With
- HTML, CSS, JavaScript - Frontend
- JSON Server - Backend

### Authors
    [Darshan Bhandwalkar]