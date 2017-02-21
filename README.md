[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/hz2py.svg)](https://hub.docker.com/r/rubygem/hz2py/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/hz2py.svg)](https://hub.docker.com/r/rubygem/hz2py/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/hz2py.svg)](https://hub.docker.com/r/rubygem/hz2py/)
[![Gem Downloads](https://img.shields.io/gem/dt/hz2py.svg)](https://rubygems.org/gems/hz2py/)
# hz2py

Auto-Generated Docker image for hz2py to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/hz2py`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/hz2py`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/hz2py`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/hz2py/)
