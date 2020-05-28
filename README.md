# TARPN Node Controller

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

Pure Python implementation of a TNC (Terminal Node Controller).

# Development

## Local setup

Create a virtualenv, activate, and install deps (using Python 3)

```
python3 -m venv venv
source venv/bin/activate
python setup.py develop
```

Now some "tarpn-" scripts are in your path. E.g.,

```
tarpn-packet-dump /tmp/vmodem0 9600
```

## Docker setup

```
docker build . -t tarpn
docker run tarpn:latest
```

# References

* https://tinkering.xyz/async-serial/
