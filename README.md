# `clean-lang` Docker image
This repository contains the Dockerfile for building a build environment for
the obscure [Clean programming language](http://clean.cs.ru.nl/Clean). It is
based on the [`buildpack-deps`](https://hub.docker.com/_/buildpack-deps/)
image, so it will also contain basic programs, such as `curl` and `git`.

## Usage
The name of the Docker image is `dsprenkels/clean-lang`. One can use the same commands as with any other image:

```shell
# start an ephemeral container and attach to it
docker run -ti --rm dsprenkels/clean-lang
```

The Clean installation will be located in `/usr/local`, so you can use the
`clm` command from any directory.

## Questions
Do you have a feature request, or just a question? Feel free to open an
issue, or just send me an email on my Github associated address.
