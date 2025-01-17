## Overview

This project showcases a basic gRPC service using Protocol Buffers for message serialization and Spring Boot as the framework. The service includes a `GreetingService` with a `greeting` method that accepts a `GreetingRequest` and returns a `GreetingResponse`.

## Prerequisites

- Java 8 or higher
- Maven or Gradle
- Protocol Buffers Compiler (`protoc`)
- An IDE like IntelliJ IDEA or Eclipse
- gRPC tools (optional for testing, such as BloomRPC or Postman with gRPC support)

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/prabhajis/demo-grpc.git
   cd demo-grpc

2. **Generate the gRPC Code:**

    Ensure protoc and the gRPC plugin are installed.
    Use Maven or Gradle to compile the .proto file:
            
    ```bash
   git clone https://github.com/prabhajis/demo-grpc.git

3. **Run the Application:**

**Testing the Service**
    You can use tools like BloomRPC or Postman to test the gRPC service:

**Using BloomRPC:**

Import your .proto file.
Set the server address to localhost:8080.
Send a request with the required parameters (e.g., message and firstname).

**Using Postman:**
Ensure you have the latest version with gRPC support.
Import the .proto file and configure the request.
Invoke the greeting method and view the response.
