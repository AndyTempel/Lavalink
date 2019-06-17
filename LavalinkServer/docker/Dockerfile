FROM openjdk:11-jre-slim

WORKDIR /opt/Lavalink

COPY Lavalink.jar Lavalink.jar

ENTRYPOINT ["java", "-Xmx4G", "-XX:+UseG1GC", "-Djdk.tls.client.protocols=TLSv1.2", "-jar", "Lavalink.jar"]
