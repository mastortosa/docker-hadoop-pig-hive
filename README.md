Based in [sequenceiq/hadoop-docker](https://hub.docker.com/r/sequenceiq/hadoop-docker/), add the latest versions of Pig and Hive.

Build the image
============

```
docker build  -t mmast/hadoop-pig-hive .
```

Pull the image
===========

```
docker pull mmast/hadoop-pig-hive
```

Start a container
=============

```
docker run -it -v /host/data/path:/opt/data mmast/hadoop-pig-hive /etc/bootstrap.sh -bash
```