FROM docker.elastic.co/elasticsearch/elasticsearch:7.1.1
# --batch for non-interactive mode (auto-confirm warnings)

RUN cd / && ls -lah
RUN /opt/elasticsearch-7.1.1/bin/plugin install lmenezes/elasticsearch-kopf


#RUN echo "xpack.security.enabled: false" >> /usr/share/elasticsearch/config/elasticsearch.yml
#RUN echo "http.cors.enabled: true" >> /usr/share/elasticsearch/config/elasticsearch.yml
#RUN echo "http.cors.allow-origin: '*'" >> /usr/share/elasticsearch/config/elasticsearch.yml
