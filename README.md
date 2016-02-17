# docker-alpine-travis-cli

[![](https://badge.imagelayers.io/jamespamplin/alpine-travis-cli:latest.svg)](https://imagelayers.io/?images=jamespamplin/alpine-travis-cli:latest 'Get your own badge on imagelayers.io')

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
