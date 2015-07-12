# ostrato
ostratoImage
this is a docker image of ostratoGranite
it was created in the following way

docker save ostratoinstall > ./ostratoinstall.tar


(A)
To use this image install docker onto an ubuntu linux system

(B)
docker load < ostratoinstall.tar

(C)
docker run --privileged -P -p 8080 -t -i ostratoupgraded  /bin/bash

