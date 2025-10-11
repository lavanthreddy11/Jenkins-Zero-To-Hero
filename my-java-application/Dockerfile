# Use official OpenJDK image
FROM openjdk:11

# Set working directory
WORKDIR /app

# Copy Java source code
COPY Main.java .

# Compile
RUN javac Main.java

# Run
CMD ["java", "Main"]