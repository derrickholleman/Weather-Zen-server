# WeatherZen Backend Application

| Folder/file path                 | Description                                                                                                           |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `src/app.js`                     | Directs requests to the appropriate routers.                                                                          |
| `src/server.js`                  | Starts the server on `localhost:5000` by default.                                                                     |
| `src/db/`                        | A folder where you will add migration and seed files for your database later on.                                      |
| `src/errors/`                    | A folder where you will find several functions for handle various errors                                   |
| `.env.sample`                    | A sample environment configuration file                                                                               |


## Database setup

1. Set up a new database.
1. After setting up your database instance, connect DBeaver to your new database.

## Installation

1. Fork and clone this repository.
1. Create an env file.
1. Update your `.env` file with a connection URL to your ElephantSQL database instance.
1. Run `npm install` to install project dependencies.
1. Run `npm run start:dev` to start your server in development mode.
