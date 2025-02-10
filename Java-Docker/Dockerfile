# FROM  openjdk
# WORKDIR /app
# ADD . .
# RUN javac HelloWorld.java
# CMD ["java", "HelloWorld"]


FROM  openjdk:11
RUN mkdir /app
COPY . /app
WORKDIR /app 
RUN  javac HelloWorld.java
CMD  java HelloWorld

