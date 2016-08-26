Containers:
* ElasticSearch with Kibana and Logstash
* Redis
* Redis Commander (WebUI)

```
# Destroy all containers
docker-compose rm

# Create continaers
docker-compose up

# Create containers in background
docker-compose up -d
```

Service URLs:
* ElasticSearch API: http://localhost:9200/_search?pretty
* Kibana: http://localhost:5601/
* Redis Commander: http://localhost:8081/
