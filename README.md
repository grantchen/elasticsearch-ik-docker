# elasticsearch-ik-docker

elasticsearch(2.1) + ik(1.6.2) plugin docker

# How to pull

```bash
docker pull grantchen/elasticsearch-ik
```
# How to start

```bash
docker run -d -p 9200:9200 -v "/home/grantchen/esdata":/usr/share/elasticsearch/data grantchen/elasticsearch-ik
```
