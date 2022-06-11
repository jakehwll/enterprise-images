# Enterprise Images

This is a multi-arch fork of the Coder [Enterprise Images](https://github.com/coder/enterprise-images) repo.

These are being built to Github's Container Registry and can be found [here](/container/enterprise-images).

This is a temporary solution until upstream these are refactored to multi-architecture.

## Image Minimums

Image Minimums
All of the images provided in this repo include the following utilities to ensure they work well with all of Coder Enterprise's features, and to provide a solid out-of-the-box developer experience:

- git
- bash
- curl & wget
- htop
- man
- vim
- sudo
- python3 & pip3
- gcc & gcc-c++ & make