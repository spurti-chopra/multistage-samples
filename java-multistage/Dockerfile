FROM java:openjdk-8-jdk-alpine
COPY HelloWorld.java . 
RUN javac HelloWorld.java

FROM java:openjdk-8-jre-alpine
COPY --from=0 HelloWorld.class . 
CMD java HelloWorld 
