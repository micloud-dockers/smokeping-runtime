# Smokeping Docker

This is a smokeping installed debian server. You can easy run the container to have a smokeping environment.

## Run

```
docker run -d -p 80:80 -v ~/dockerws/smokeping/config.d:/etc/smokeping/config.d peihsinsu/smokeping
```

In this content, I put the smokeping contents to config.d and mount to the instance.

```
simonsu@simon-debian6:~/dockerws/smokeping/config.d$ ls -l
total 32
-rwxr-xr-x 1 simonsu simonsu  177 Mar 26 10:24 Alerts
-rwxr-xr-x 1 simonsu simonsu  236 Mar 26 10:45 Database
-rwxr-xr-x 1 simonsu simonsu  505 Mar 26 10:44 General
-rwxr-xr-x 1 simonsu simonsu  876 Mar 26 10:24 Presentation
-rwxr-xr-x 1 simonsu simonsu   83 Mar 26 10:24 Probes
-rwxr-xr-x 1 simonsu simonsu  147 Mar 26 10:24 Slaves
-rwxr-xr-x 1 simonsu simonsu 2334 Mar 26 10:24 Targets
-rwxr-xr-x 1 simonsu simonsu  225 Mar 26 10:24 pathnames
```

