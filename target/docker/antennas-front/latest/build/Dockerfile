FROM quay.io/jkube/jkube-java:0.0.13
ENV JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0 JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-05-18T16:53:24.363370 org.label-schema.name=antennas-front org.label-schema.vcs-ref=dd5dfa95410afa5b6d4c9b96586b5fd5b68e1e7b org.label-schema.vcs-url=https://github.com/sebastienblanc/antennas-front
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
WORKDIR /deployments
