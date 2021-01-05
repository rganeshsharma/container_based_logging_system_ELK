
ELK Deepdive
Complete guide to develop and deploy ELK solutionon On-premise and Hyperscalers environment

ELK is one of the most popular cloud monitoring solutions that is used to store, monitor and analyze both metrics and logs from a variety of cloud and on-premise resources. Broadly the ELK Stack comprises of Elasticsearch, Logstash, Beats and Kibana. The basic functionality of each of these components of ELK stack is as follows :
Elasticsearch is the heart of the solution which comprises of a distributed JSON based search and analytics engine. It acts like a central repository for storing data and helps us query any details from it.
These data can be logs, metrics, Application Performance Metrics and many more
Logstash is a open source data processing pipeline which dynamically ingests, transforms, and ships your data regardless of format or complexity to Elasticsearch where it can be stored. The main function of Logstash is that it provides capabilities to parse and transform data before it can be stashed into Elasticsearch or we can use Logstash API’s to build any plugins
Beats is a lightweight agent that ships the data from various sources to Elasticsearch. Types of beats are as follows:
Filebeat for collecting logs and its related data
Metricbeat for collecting metric data like CPU, Memory and other metrics
Packetbeat for collecting network data
Winlogbeat for collecting Windows event logs
Auditbeat for collecting audit data
Heartbeat for collecting uptime monitoring of different components
Functionbeat for collecting cloud data
Kibana is the UI or the dashboard component of ELK Stack which helps us configure Elasticsearch cluster its indexes and shards, perform many other operations on Elasticsearch. Kibana has hundreds of features capabilities and not all of them is discussed here. Some of the most important Kibana functions are listed as follows:
Create Visualizations by dragging and dropping the appropriate fields
Create Dashboards which can be a combination of number of Visualizations
Query the cluster using CRUD style APIs
Create Alerts to trigger specific actions


Deployment:
ELK deployment on Cent OS based VM's
ELK deployment on Azure AKS 

ELK Architechture, configuration and functionality of each components?
ELK sizing? Scaling up?
ELK storage used and why? (PV in Azure File storage)
Backup and DR startegy?
Retention policy set?

visit www.virtualgyaan.com for more details
