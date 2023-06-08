# wp_docker
Pure wordpress+mysql+phpmyadmin in docker setup

## ENV
Edit .env from docker/ to customize env params

## RUN
To run this setup go to docker/ and execute docker compose up
```
cd docker;
docker compose up
```

After that docker will build all images and run them
You will have to go through WP setup

### Access
Wordpress
> http://localhost:${WP_PORT}

PhpMyAdmin
> http://localhost:${PMA_PORT}
