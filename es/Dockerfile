FROM elasticsearch:latest

RUN plugin -i elasticsearch/marvel/latest
RUN plugin -install mobz/elasticsearch-head

EXPOSE 9200
EXPOSE 9300
