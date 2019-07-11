FROM java:8
RUN mkdir -p /build
COPY airports-assembly-1.0.1.jar /build/airports-assembly-1.0.1.jar
RUN cd /build
WORKDIR /build
CMD ["java", "-jar", "airports-assembly-1.0.1.jar"]
