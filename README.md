# docker-alpine-travis-cli

Small docker image for the CLI to [Travis CI](http://travis-ci.org/).

To run (in your project directory):

```sh
docker run -it --rm -v `pwd`:/data -v $HOME/.travis:/root/.travis jamespamplin/alpine-travis-cli
```

Mount your project directory to `/data` in the container.

Mount your travis configuration to `/root/.travis` in the container.


Thanks to [@cybercode's](https://github.com/cybercode)
[alpine-ruby](https://github.com/cybercode/alpine-ruby) image for C compilation
dependencies.
