# Portfolio-Deployment-Using-Docker

This project contains a static website that is deployed using Docker. The website is served using Nginx inside a Docker container.

## Project Overview

- **Dockerfile**: This file defines the Docker configuration, which includes using the Nginx web server to host the static files.
- **index.html**: The main HTML file for the static website.
- **styles.css**: Stylesheet for the website.
  

## Getting Started

To build and run this project in Docker, follow the steps below:

### Build the Docker Image

```bash
docker build -t my-static-website .
