## Setup

Prepare `docker-compose` environment

    cp .env-dist .env

and application    
    
    cp config/app.env-dist config/app.env
    mkdir web/assets

Start stack

    docker-compose up -d

Show containers

    docker-compose ps

Run composer installation

    docker-compose run --rm php composer install


## Develop

Create bash    
    
    docker-compose exec php bash

Run package update in container    
    
    $ composer update -v

...

    $ yii help

      
## Test

    cd tests
    cp .env-dist .env


#### ![dmstr logo](http://t.phundament.com/dmstr-16-cropped.png) Built by [dmstr](http://diemeisterei.de)
