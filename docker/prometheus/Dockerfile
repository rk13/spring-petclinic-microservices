FROM prom/prometheus:v2.4.2

ADD 'https://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=com.datadoghq&a=dd-java-agent&v=LATEST' dd-java-agent.jar
ADD prometheus.yml /etc/prometheus/
