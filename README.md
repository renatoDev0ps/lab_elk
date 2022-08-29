# ELK (Elasticsearch + Logstash + Kibana) 7.6.2 with Docker

```
sudo su -
```

```
docker-compose up -d
```

* User `elastic` and password `123change...`
* Elasticsearch: http://localhost:9200
* Kibana: http://localhost:5601
* For logstash demo, see confs in `logstash/conf` dir
* CSV used to load data is in `logstash/csv` dir
* For elasticsearch configuration, see `elasticsearch.yml` in `elasticsearch/config` dir
* Search for test `http://localhost:9200/_search`
