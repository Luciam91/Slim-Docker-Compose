# Slim Framework 3 Skeleton with Docker-Compose

Don't want to run Slim with the internal web server? Now you can run it with Docker! Just ensure you have docker-compose installed, clone the project and do a `docker-compose up` and you're ready to go!

Note: If you choose to keep the MySQL container you should start it first using `docker-compose up -d database` and waiting 10-20 seconds before running `docker-compose up`

Further updates will follow including:

- Adding a database container (MySQL / Postgres) - MySQL Container Added (2/8/2016)
- Adding a caching layer (Memcached/Redis) - Redis container added (2/8/2016)
- Environment specific config files