![GitHub](https://img.shields.io/github/license/Jannik2099/gentoo-travis-ci) ![Travis (.com)](https://img.shields.io/travis/com/Jannik2099/gentoo-travis-ci)

# gentoo-travis-ci
This project is a travis CI for gentoo overlays. It runs a FEATURES=test emerge on all modified ebuilds in a push / pull request.
It uses my [docker containers](https://hub.docker.com/repository/docker/jannik2099/gentoo) as a build environment. Currently implemented are amd64 and arm64.

## How to use
Copy the contents of src into your overlay
Edit the env section of .travis.yml to include the packages in your overlay
