# use an official java image
FROM openjdk:17

# set the working directory inside the container
WORKDIR /app

# copy the java file into the container
COPY Main.java .

# Compile the java file
RUN javac Main.java

# set the command to run the program
CMD ["java", "Main"]
