Running Github Actions locally via [act](https://github.com/nektos/act) requires a Docker image.

By default, they provide a `node` official image, but in the context of building Docker images via Github actions, you also need `docker` installed on top of `node`.

This is exactly what this image does: `node` + `docker` = 🚀