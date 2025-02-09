# Agentic-RAG-Elasticsearch

* to run this code you have to have access to an ElasticSearch API I used following Docker image.
  
docker run -p 9200:9200 -d --name elasticsearch_new \
-e "discovery.type=single-node" \
-e "xpack.security.enabled=false" \
-e "xpack.license.self_generated.type=trial" \
-v "elasticsearch-data:/usr/share/elasticsearch/data" \
docker.elastic.co/elasticsearch/elasticsearch:8.15.0

* It work with colab and you can By changing indexing and Querys use it for any language not only persion
