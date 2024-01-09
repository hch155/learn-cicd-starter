# learn-cicd-starter (Notely)

![code coverage badge](https://github.com/hch155/learn-cicd-starter/actions/workflows/ci.yml/badge.svg)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

This README is for reference purposes only! Follow the instructions in the course, don't start doing all the steps here in the README.

## Local Development

Make sure you're on Go version 1.20+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8000"
```

Run the server:

```bash
go build -o notely && ./notely
```
