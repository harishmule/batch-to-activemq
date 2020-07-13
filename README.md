##########################################################
- Welcome to  "batch-to-activemq"
- This API is to lear batch and active mq
	- We get the flight details from Flights API which is provided in training classes by mulesoft
	- We send those data to Batch and process and then to Mq
##########################################################
- This API is implemented by using below
	* Mule4
	* Runtime version 4.2.2
	* HTTP Listener
	* HTTP Requester
	* Batch
	* JMS
##########################################################
- Getting started
	1) clone project 
	2) Import jar into anypoint studio 7 (mule 4)
	3) Make sure you'll get all files 
	4) Please install active mq and run (download: ActiveMQ 5 "Classic": https://activemq.apache.org/) 
	5) Start the active mq server in local and open it in browser by using: http://localhost:8161/ --> username and password is admin
	6) Right click the application and RUN in anypoint studio
	7) To execute the application: http://localhost:8081/flights
##########################################################



