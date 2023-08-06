#getting base image from docker hub
FROM openjdk:11

#create working directory where all codes will be kept
WORKDIR app/

#copy app code from system to current working directory of container
COPY Hello.java .

#Compile code
RUN javac Hello.java

#Run java compiled code
CMD ["java","Hello"]
