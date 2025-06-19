## LDC Via support, a ticketing system

> Ticket system application built with the [MERN stack](https://www.mongodb.com/resources/languages/mern-stack) that allow teams to manage bugs, requests, and other support tickets.

![Ticket System Dashboard Home](/public/assets/screenshots/ticket_system_dashboard_home.png)

### Built with
* Mongoose.js (MongoDB): Database
* Express.js: Backend framework
* React.js: Frontend framework
* Node.js: Runtime environment

### Original author
This is a fork of [Vector Le's app](https://github.com/VectorLe/ticket-system), with some breaking changes incorporated, to try and bring it up to date and (more) secure.

### Running…
To run the app, do a simple `npm start` once you've installed dependencies. By default it will be in error, because it expects a MongoDB connection. To resolve all that, create a copy of `.env.template`, name it `.env` and configure the `ATAS_URL` variable with a valid MongoDB Atlas connection string.

### TODO
Additional docs pending…

_19-Jun-2025_
