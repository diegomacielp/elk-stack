# Elastic Stack

<p align="justify">"ELK é o acrônimo para três projetos open source: Elasticsearch, Logstash e Kibana. O Elasticsearch é um mecanismo de busca e análise. O Logstash é um pipeline de processamento de dados do lado do servidor que faz a ingestão de dados a partir de inúmeras fontes simultaneamente, transforma-os e envia-os para um "esconderijo" como o Elasticsearch. O Kibana permite que os usuários visualizem dados com diagramas e gráficos no Elasticsearch."</p>

<div id="topicos"></div>

* [Tópicos](#topicos)
    - [Elasticsearch](#elasticsearch)

<div id="elasticsearch"></div>

## Elasticsearch

1. Iniciando Elasticsearch:
### 
    docker-compose up -d elasticsearch
    curl localhost:9200

<p align="center">
  <a><img src="./imgs/elasticsearch.png"></a>
</p>

2. Testando Elasticsearch: