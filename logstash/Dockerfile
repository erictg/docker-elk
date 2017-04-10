# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.3.0

# Add your logstash plugins setup here
RUN logstash-plugin install logstash-filter-json

RUN logstash-plugin install logstash-input-log4j

RUN logstash-plugin install logstash-output-file

RUN logstash-plugin install logstash-input-tcp
