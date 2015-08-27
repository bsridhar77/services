# services
Repo for POC Microservices

To Build the project ( Builds a jar not a WAR ) 

	mvn package
	
	
To Run the service
	
	java -jar target/agentservice-0.0.1-SNAPSHOT.jar server agentservice.yml
	
	
The Port on which the agent service runs is configured in agentservice.yml

http://localhost:9080/agent/1	

http://localhost:9080/agent/1
