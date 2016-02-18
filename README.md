# DockerLab <br>
<br>
This is a repo that will deploy a Docker container running two node Couchbase cluster with and additional instance running go-beer-sample, node-travel-sample and a java environment. The goal is to run a single step for automated deployment.
<br>
1. Install Docker ... https://docs.docker.com/v1.5/installation/<br>
2. Once complete run Docker terminal <br>
3. Clone the Couchbase Day repo "git clone https://github.com/justinmichaels006/DockerLab.git" <br>
4. This should create the DockerLab directory. "cd DockerLab" <br>
5. Run the deployCouchbase script. "./deployCouchbase" <br>
<br>
<br>
Clean Up: <br>
1. Stop each of the three "CONTAINER ID" created above "docker stop <container>". To find the ID's use "docker ps". <br>
2. Remove the containers using "docker rm <container>". <br>
3. Be sure to also remove the directories created for each node. "sudo rm -R ~/cbDay" <br>
<br>
TODO: <br>
1. Auto provision the travel-sample application. Right now this can be provisioned manually by editing the config.json but this should be automated. <br> 
2. Add the beer-sample application views that are needed as well as automate the creation of beer-sample. This could be a good lab to add to the CB Days as well? <br>
3. Add the JAVA Loading lab as well as the labs around GO and Node asynch.
4. How much can be distributed locally via zip files with no use of wget/yum/etc?
 
