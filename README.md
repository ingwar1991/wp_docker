# wp_docker
Pure wordpress+mysql+phpmyadmin in docker setup

#### Ignoring WP plugins dir
For my own purposes I added wp plugins dir to .gitignore

You'll need to remove the first entry from the file
> /project/my_plugins
> /project/wp-content/plugins/*

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
