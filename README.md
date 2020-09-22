# Spin up Jenkins CI server

## Increase the virtual memory for Elastic Search
sudo sysctl -w vm.max_map_count=262144


## To start Jenkins CI server
Run `./start-jenkins.sh`

For getting default password, run `docker exec -it jenkins cat /var/jenkins_home/secrets/initialAdminPassword`


## Access the Jenkins CI server
Navigate to `http://localhost:8081`
