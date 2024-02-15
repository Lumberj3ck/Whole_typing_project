
# Whole Typing Project

Whole Typing Project is a web application that combines a Django API with a Vue.js frontend. It is designed to provide a convenient and efficient platform for typing-related tasks. This guide will help you set up and run the project, with additional details and insights into its functionality.

## Demo

[Working demo](http://typer.us.to/). The demo is hosted on Digital Ocean servers.

## Prerequisites

Before you can run the project locally, make sure you have the following tools and technologies installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Git (for cloning the repository)

## Getting Started

1. Clone this repository to your local machine
```
git clone --recursive https://github.com/Lumberj3ck/Whole_typing_project/
```
2. Navigate to project directory
```
cd Whole_typing_project
```
3. Add your host to allowed hosts variable
```
vim ./typing_trainer_rest/.env.prod
```
4. Change site url in config.js
```
vim ./frontend_vue/src/config.js
```
5. Docker start
```
docker compose build
docker compose up
```
If you encountering issues try to prune volumes and build up again

