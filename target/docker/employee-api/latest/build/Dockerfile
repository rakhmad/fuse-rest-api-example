FROM fabric8/s2i-java:2.3
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Spring Boot example running a Camel route defined in XML" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2020-10-13T20:14:31.286 org.label-schema.name="Fabric8 :: Quickstarts :: Spring-Boot :: Camel XML" org.label-schema.vcs-ref=8ab590a4956b427ae02930c5bcb4c3cead6d8f11 org.label-schema.vcs-url=https://github.com/mhockelberg/fuse-rest-api-example.git
EXPOSE 8080 8778 9779
COPY maven /deployments/
