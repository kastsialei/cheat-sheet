# Cheat-sheet
Contains useful for me and my work scripts and commands

# TOC

- Short useful commands
- Docker
- Git

# Short useful commands

## rsync and ssh on different port

`rsync -avz -e "ssh -p $portNumber" SOURCE DEST`

## SSH

- `ssh  -C -c blowfish-cbc,arcfour` ssh compression
- `ssh root@server1 'df -H'` ssh + disk usage

## Docker

 - Clean unused containers and volumes
 - `docker exec -it CONTAINER_HASH /bin/bash`
 - clean logs of container : `truncate -s 0 /var/lib/docker/containers/$CONTAINER_HASH/$CONTAINER_HASH-json.log`
 ## Git

 - Amend

## Bash
sudo !! - run previous bash command as sudo, for example if you typed it without sudo and want to rerun
