# docker-gvm - a Docker container for GVM

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-gvm/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-gvm:latest bash -lic 'gvm version'
Groovy enVironment Manager 2.4.3
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
