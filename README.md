# DevStage App API

This is the backend API for the NLW Connect project. It provides endpoints for managing and connecting users within the platform.

This is a [Node.js](https://nodejs.org/) project built with:
- [Fastify](https://fastify.dev/)
- [Redis](https://redis.io/)
- [Postgres](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

I've built during the NLW Connect: an awesome event by [RocketSeat](https://www.rocketseat.com.br/)

The main objective of this project is to create an API from scratch to better understand node.js.


## Installation

1. Clone the repository:
    ```
    git clone https://github.com/AndreiPrado/nlw-connect-nodejs
    ```
2. Navigate to the project directory:
    ```
    cd nlw-connect-nodejs
    ```
3. Install the dependencies:
    ```
    npm install
    ```
4. Start the docker containers:
    ```
    docker compose up -d
    ```
5. Create DB migrations:
    ```
    npm run db:migrate
    ```

## Usage

1. Duplicate .env.sample file creating a .env with the required information.

2. Start the development server:
    ```
    npm run dev
    ```
2. The API will be available at `http://localhost:PORT`. (PORT will be defined in the .env file)

## Deployed using Render

I've deployed using [Render](https://render.com/) and connected with the front-end application using React. ([Here](https://github.com/AndreiPrado/nlw-connect-react))

You can check the [Documentation Here](https://nlw-connect-nodejs-5rya.onrender.com/docs)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
