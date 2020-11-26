
## Installation
Go to WSL2:

git clone https://github.com/big-data-europe/docker-hive.git
cd docker-hive
docker-compose up -d

docker exec -it docker-hive_hive-server_1 /bin/bash
/opt/hive/bin/beeline -u jdbc:hive2://localhost:10000

## GUI Database management
DBeaver



