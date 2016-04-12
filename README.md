# docker-beanstalk-console

Admin console for Beanstalk queue server, written in PHP.

See https://github.com/ptrofimov/beanstalk_console

# Usage

This docker image is available as a [build on the docker hub](https://hub.docker.com/r/kusmierz/beanstalk-console/), so there's no setup required.
Using this image for the first time will start a download automatically.
Further runs will be immediate, as the image will be cached locally.

The recommended way to run this container looks like this:

```bash
$ sudo docker run -d -p 80:80 kusmierz/beanstalk-console
```

The above example exposes the Beanstalk Console webinterface on port 80, so that you can now browse to:

```
http://localhost/
```

