Use cases
# ntucCoaching20241221flask-python
# m3.3activity

`using`
https://github.com/docker/build-push-action

https://hub.docker.com

# check logged-in Docker Hub Username
```
$ docker info | grep Username
```
# check remote tags in Docker Hub Repo
$ curl -s "https://hub.docker.com/v2/repositories/<your-dockerhub-username>/<repo-name>/tags/" | jq -r '.results[].name'

$ curl -s "https://hub.docker.com/v2/repositories/rger/flask-app/tags/" | jq -r '.results[].name'
asd