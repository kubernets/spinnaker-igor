# spinnaker-igor

github addr [https://github.com/kubernets/spinnaker-igor](https://github.com/kubernets/spinnaker-igor)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/spinnaker-igor/raw/master/get-spinnaker-igor-image.sh

## Arch and Version

- [**all** 0.9.0-20180221133510](https://hub.docker.com/r/kubernets/spinnaker-igor)

    > docker pull kubernets/spinnaker-igor:0.9.0-20180221133510

    > docker tag kubernets/spinnaker-igor:0.9.0-20180221133510 gcr.io/spinnaker-marketplace/igor:0.9.0-20180221133510 

    > docker rmi kubernets/spinnaker-igor:0.9.0-20180221133510
