# Kibana

Kibana 3 milestone 2

Uses nginx to front the new Kibana

* `docker build -t kibana .`
* `docker run -d -p 80:80  kibana`  // assumes elastic search is running on the same host and on port 9200, override it through run.sh

Ports

* 80 (kibana)
