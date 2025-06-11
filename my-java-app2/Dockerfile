# use an official java image
FROM openjdk:17

# set the working directory inside the container
WORKDIR /app

# copy all .java files into the container
COPY *.java .

# Compile all java files
RUN javac *.java

# set the command to run the Main class
CMD ["java", "Main"]
