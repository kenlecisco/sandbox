FROM docker.elastic.co/logstash/logstash:7.15.2

RUN /usr/share/logstash/bin/logstash-plugin install logstash-codec-msgpack

CMD ["-f", "/usr/share/logstash/pipeline/logstash.conf"]
