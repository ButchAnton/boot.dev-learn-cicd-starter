![CI/CD Status](https://github.com/ButchAnton/boot.dev-learn-cicd-starter/actions/workflows/ci.yml/badge.svg)

# learn-cicd-starter (Notely)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

## Local Development

Make sure you're on Go version 1.22+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server:

```bash
go build -o notely && ./notely
```

_This starts the server in non-database mode._ It will serve a simple webpage at `http://localhost:8080`.

You do _not_ need to set up a database or any interactivity on the webpage yet. Instructions for that will come later in the course!

Butch's version of Boot.dev's Notely app.

## Contributing

### Clone the repository

```bash
git clone https://github.com/ButchAnton/boot.dev-learn-cicd-starter@latest
cd boot.dev-learn-cicd-starter
```

## Build the project

```bash
go build -o notely
```

### Run the project

```bash
./notely
```

### Submit a pull request

If you'd like to contribute, please fork the repository and open a pull request to the `main` branch.
