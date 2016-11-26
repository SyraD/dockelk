# ELK v2.4
Docker logging stack: 
 - ElasticSearch 
 - Logstash Indexer
 - Redis Broker
 - Logstash Shipper
 - Kibana
 - Docker GELF driver

Flow:

container -> docker gelf -> logstash shipper -> redis -> logstash indexer -> elasticsearch -> kibana
