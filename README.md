# ocrmypdf

This is a container makes usage of ocrmypdf easy, just run the container and pass the pdf to the container.

```bash
docker run -v $(pwd):/tmp/input athalonis/ocrmypdf test.pdf
```

The `test.pdf` will be copied to `test_copy.pdf` and the ocred version will be test.pdf

A prebuild container can be found on [hub.docker.com](https://hub.docker.com/repository/docker/athalonis/ocrmypdf)
