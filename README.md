# ScriptsAndTools

A collection of scripts I have made for myself.

## update-server-containers

This script downloads the latest "latest" image for all images where we have a latest image. Basically updates all containers where we do not
use a specific tag

It cleans up/prunes old containers and images

I also updates the machine it runs on (apt update/upgrade) .

I use this to keep my docker based servers up to date.  Use at own risk. You may want to control
the version of the containers more explicitly.




