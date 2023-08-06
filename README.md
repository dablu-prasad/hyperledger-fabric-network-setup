# hyperledger-fabric-network-setup


coach db
-----------------

http://localhost:5984/_utils/#login

- COUCHDB_USER=admin
- COUCHDB_PASSWORD=adminpw

curl -sSL https://bit.ly/2ysbOFE | bash -s -- 2.1.0 1.4.6 0.4.18



docker rm -f $(docker ps -aq)
docker rmi -f $(docker images -q)
docker rmi -f $(docker images | grep dev-peer[0-9] | awk '{print $3}')
docker network prune


./network.sh down
./network.sh up createChannel

5 attempt error
---------------------------
https://stackoverflow.com/questions/60172883/fabric-v2-0-in-kubernetes-minikube-error-peer-channel-error-validating-pro


chanel create error-
-------------------------

channelID  in place of --channel--id



