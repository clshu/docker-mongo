# volume location

## Window

- C:\ProgramData\docker\volumes

## Linx

- /var/lib/docker/volumes

## Mac OS

### Docker for Mac creates a Linux virtual machine and stores all the Docker data there

### After login VM, the location for named volumes `mongo-db` is

- /var/lib/docker/volumes/mongo_mongo-data/\_data

- Working command

```
$ docker run -it --rm --privileged --pid=host
justincormack/nsenter1
```

- Not working commans

```
$ screen ~/Library/Containers/com.docker.docker/Data/com.docker.driver.amd64-linux/tty
$ screen ~/Library/Containers/com.docker.docker/Data/vms/0/tty


```
