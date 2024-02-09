# WP + Bedrock + Docker
A template to get bedrock rordpress running on docker;

Requires docker and composer.

## Create an .env file and edit as necessary
````
$ cp bedrock/.env.example bedrock/.env
````

## Install WP and composer composer dependecies
````
$ cd bedrock && composer install
```` 

## Launch containers
````
$ docker-compose up
````

## That's it
Navigate to [http://localhost](http://localhost) and start the WP install.