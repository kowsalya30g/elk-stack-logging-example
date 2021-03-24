# elk-stack-logging-example
How to perform centralize logging in microservice architecture using ELK Stack

###### Download ELK Binary Distrubution

###### 1.Elastic Search [Download](https://www.elastic.co/downloads/elasticsearch).
###### 2.Logstash [Download](https://www.elastic.co/downloads/kibana).
###### 3.Kibana [Download](https://artifacts.elastic.co/downloads/logstash/logstash-7.6.2.zip).



##### Run elastic batch file and kibana batch file 

# Go to the Spring project and do the following steps 

Open a spring boot porject and edit the application.yml with the credentials of pathname of logs and run it 

Then create a log stash conf file which has that path of the mentioned log from the spring and run the logstash 

````
logstash -f ../logstash.conf
````
# Then open kibana dashboard and see the logs 
