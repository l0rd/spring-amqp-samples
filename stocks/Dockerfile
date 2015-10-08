FROM jetty
COPY /target/spring-rabbit-stocks-1.5.0.RELEASE.war /usr/local/jetty/webapps/
RUN java -jar "$JETTY_HOME/start.jar" --add-to-startd=jmx,stats
