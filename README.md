# Elastic Stack

<https://whimsical.com/elastic-stack-JXaBVoyajHpSHz47HJAHfx>


## Elasticsearch

Elastic Search é um banco de dados NoSQL orientado a documentos.  
Também provê uma API Rest para registro e consulta de dados.


## Kibana

O Kibana é uma aplicação gratuita e aberta de front-end que trabalha com o Elastic Stack, fornecendo recursos de busca e visualização de dados indexados no Elasticsearch. Comumente conhecido como a ferramenta de gráficos para o Elastic Stack.

## Logstash

O Logstash é um pipeline gratuito e aberto de processamento de dados do lado do servidor que faz a ingestão de dados de inúmeras fontes, transforma-os e envia-os para o seu "repositório" favorito, inclusive para o Elasticsearch.

...

As três ferramentas acima compõem a ELK (Elasticsearch, Logstash e Kibana).

## Beats

O Beats é uma plataforma gratuita e aberta para **agentes** de dados de finalidade única. Eles enviam dados de centenas ou milhares de computadores e sistemas para o Logstash ou o Elasticsearch.

Em vez de as aplicações terem que enviar dados/logs para o Logstash ou Elasticsearch, esse agent (Beats) fica coletando os logs no servidor que está instalado e enviando para Logstash ou Elasticsearch.

...

Sim, os logs podem ser enviados direto para Elasticsearch. Se, porém, for necessário fazer algum **enriquecimento** nos dados, o Logstash seria a ferramenta ideal para intermediar essa ingestão e transformação.




### Grok debugger:

<http://0.0.0.0:5601/app/dev_tools#/grokdebugger>

Grok patterns:

<https://github.com/hpcugent/logstash-patterns/blob/master/files/grok-patterns>

<https://www.elastic.co/guide/en/logstash/current/plugins-filters-grok.html>
