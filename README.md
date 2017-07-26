# Inkscape Docker

Alpine based Docker image with Inkscape. Created to perform command line Inkscape operations as part of a continuous integration build process. Extended by [flungo/inkscape-plus](https://hub.docker.com/r/flungo/inkscape-plus/) to provide additional tools and utilities.

## Usage

```cli
docker pull flungo/inkscape
docker run -it flungo/inkscape /usr/bin/inkscape --help
```
