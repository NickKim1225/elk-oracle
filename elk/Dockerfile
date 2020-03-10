FROM sebp/elk


COPY ./logstash-oracle.conf /logstash-oracle.conf
COPY ./ojdbc7.jar /ojdbc7.jar

RUN chmod 777 -R /opt/logstash/data
RUN cd / && pwd && ls -lah

#WORKDIR $LOGSTASH_HOME

RUN pwd && ls -lah
