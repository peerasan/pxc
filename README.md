# pxc
Percona XtraDB Cluster


docker run --restart=always -p 3306:3306 -p 4444:4444 -p 4567:4567 -p 4568:4568  --name node1 -h node1 -t -i -d patrickz/pxc /bin/bash