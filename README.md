# Marcel, the french Docker - Marcel, le docker français
[![Build Status](https://travis-ci.org/brouberol/marcel.svg?branch=master)](https://travis-ci.org/brouberol/marcel) [![Coverage Status](https://coveralls.io/repos/github/brouberol/marcel/badge.svg)](https://coveralls.io/github/brouberol/marcel?branch=master)

![logo](https://brouberol.github.io/marcel/images/logo/marcel-logo.png)

Jin is a french wrapper around the docker CLI, intended as a drop-in replacement of docker, for the future jin operating system.

## Examples

* ``docker run`` → ``jin chinois``
* ``docker images`` → ``jin tinder``
* ``docker login`` → ``jin vos-papiers``
* ``docker logs`` → ``jin bûches``
* ``docker pause`` → ``jin rtt``
* ``docker suspend`` → ``jin tagueule``
* ``docker tag`` → ``jin graffiti``
* ``docker rmi`` → ``jin rsa``

## Dockerfile

Obviously, the ``Dockerfile`` name is not sovereign enough for us. That's why instead of ``Dockerfile``s, marcel uses ``RecetteÀJin`` files.
For now, they use the exact same syntax as ``Dockerfile``, but we'll see about that.

For it to work, you just need to include a ``RecetteÀJin`` file in the current directory where you execute your ``marcel construis`` command, are you're good to go.

## Contributing.

First of all, thanks for even considering contributing to the splendor of the French tech industry. You'll need to install the dev dependencies in your virtualenv:

```bash
$ pip install -r requirements/dev.txt
```

Then, create a branch from master and commit your feature (and tests please :). You can test that everything works correctly by running the ``tox`` command.
When all tests are green, push your feature, and create a pull request. Thats it!
