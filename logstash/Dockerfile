# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.2.1

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

ADD ./pipeline/logstash.conf /etc/logstash/conf.d/
