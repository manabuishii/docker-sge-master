# docker-sge-master
Docker Grid Engine master

# How to use

```
docker run  --hostname sgemastertest -e RUNUSER_USERNAME=docker -e RUNUSER_UID=1000 -e RUNUSER_GID=100 -e RUNUSER_HOME=$HOME -v $HOME:$HOME:ro  --rm  -ti  --name sgemastertest manabuishii/docker-sge-master:0.1.0 /bin/bash
```

```
/usr/local/bin/setup_gridengine.sh
```

```
echo "hostname ; date" | qsub
```

```
ls -l /root
```

# About log files

About log files

[Rotating and truncating Sun Grid Engine Log Files](http://gridscheduler.sourceforge.net/howto/rotatelogs.html)

