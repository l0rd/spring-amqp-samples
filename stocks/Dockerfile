FROM maven:3-jdk-7
COPY / /usr/src

WORKDIR /usr/src

RUN mvn clean install
CMD mvn exec:java -Dexec.classpathScope=test -Dexec.mainClass=org.springframework.amqp.rabbit.stocks.Server
