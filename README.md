# Findora API Gateway

## Student Information
- **Student Name:** Charuka Hansaja[cite: 2]
- **Student ID:** c44073838[cite: 2]
- **Slack Handle:** Charuka (`U0BF12U29NF`)[cite: 2]
- **GCP Project ID:** findora-cloud-platform[cite: 2]

---

## Project Description
The API Gateway component acts as the single entry point for all client requests entering the Findora backend system. It handles request routing, load balancing, and integration with the Eureka Service Registry.

## Technology Stack
- **Language:** Java 25[cite: 2]
- **Framework:** Spring Boot, Spring Cloud Gateway, Netflix Eureka Client[cite: 2]
- **Process Manager:** PM2[cite: 2]

## Setup / Getting Started Instructions
```bash
# Build the project
mvn clean package -DskipTests

# Run locally
java -jar target/api-gateway-0.0.1-SNAPSHOT.jar