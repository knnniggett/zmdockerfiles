# zmdockerfiles
This repository contains Docker files used for running the latest code from the ZoneMinder master branch.
These are not intended for production. See the [release](https://github.com/ZoneMinder/zmdockerfiles/tree/master/release) folder if you are looking to run ZoneMinder inside Docker for production.

Contributions are welcome, but please follow these simple guidelines:

- Only one Dockerfile per distro
- Keep each Dockerfile sorted by distro
- Each Dockerfile should be self sufficient. It should grab the ZoneMinder project, and any other other requried files, from github or other online resource, rather than expect files to pre-exist on the filesystem.

