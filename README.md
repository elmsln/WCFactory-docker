# wcfactory-docker [In development]

We include a docker-compose file for developement purposes which has the monorepo pre-installed.  It also has
the cli globally available in the image.

To run wcfactory cli commands inside of the docker image you can run the follow command:

Examples
```bash
docker-compose run wcf <command>
docker-compose run wcf factory
docker-compose run wcf new
```

Anything created inside of the docker image will be synced locally inside of the `./tmp/docker/wcfactory` directory.
