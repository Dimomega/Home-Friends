# Projet SEO


## Docker

## Build the environment

docker-compose up -d --build

## Install the project dependencies

docker-compose run app npm install

## Run the local server

docker-compose run --service-ports app npm start