Currently stuck trying to deduplicate environment variables (storing them all in `.env` to be auto-loaded by docker-compose), but not sure how I'm going to "interpolate" those variables into `config.yml`.

The whole reason I even want verdaccio set up with s3 is so that I could control the lifecycle of the actual package files stored in S3, but I guess it just wasn't meant to be.

## Resources

- https://docs.docker.com/compose/gettingstarted/
- https://verdaccio.org/docs/en/docker
- https://docs.min.io/docs/minio-docker-quickstart-guide.html
- https://stackoverflow.com/questions/14469515/how-to-npm-install-to-a-specified-directory
- https://docs.docker.com/compose/environment-variables/#the-env-file
- https://github.com/verdaccio/monorepo/tree/master/plugins/aws-s3-storage
- https://github.com/verdaccio/monorepo/blob/master/plugins/aws-s3-storage/docker-compose.yaml
- https://github.com/verdaccio/monorepo/blob/master/plugins/aws-s3-storage/Dockerfile
- https://github.com/verdaccio/monorepo/blob/master/plugins/aws-s3-storage/conf/config.yaml
