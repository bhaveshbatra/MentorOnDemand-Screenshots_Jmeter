FROM openjdk:latest

# Add Maintainer Info
LABEL maintainer="bhavesh.avb@gmail.com"


ADD target/ModMentor.jar ModMentor.jar

EXPOSE 10012

# Run the jar file 
ENTRYPOINT ["java","-jar","ModMentor.jar"]