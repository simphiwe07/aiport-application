FROM java:8
RUN mkdir -p /build
COPY countries-assembly-1.0.1.jar /build/countries-assembly-1.0.1.jar
RUN cd /build
WORKDIR /build
CMD ["java", "-jar", "countries-assembly-1.0.1.jar"]