# AI Helpdesk Ticket System (Tool Calling)

A simple Spring Boot application that demonstrates AI Tool Calling using Spring AI. The application listens to customer requirements, automatically creates a helpdesk ticket in a local database, and responds to the customer accordingly.

## Key Features

Intelligent Tool Calling: Uses Spring AI and OpenAI to understand customer requests and trigger Java functions.

Automated Ticket Creation: Automatically generates a HelpDeskTicket entity based on the customer's prompt.

H2 Database Integration: Uses a file-based H2 database to persist ticket data locally.

Smart Responses: The AI formulates a natural response to the customer confirming the ticket details.
 
### Tech Stack

Java & Spring Boot

Spring AI (OpenAI model)

H2 Database (File-based)

Spring Data JPA

### How to Run

Clone the repository:

git clone https://github.com/Rajnish-chauhan/SpringAi-ToolsCalling


### Set your OpenAI API Key:
Make sure to set your environment variable before running:

export OPENAI_API_KEY="your-api-key-here"


### Run the Application:
Start the Spring Boot app from your IDE or via Maven/Gradle.

### View the Database:

Go to http://localhost:8080/h2-console in your browser.

JDBC URL: jdbc:h2:file:C:\Users\crajn\toolsCalling;AUTO_SERVER=true (Adjust path if needed)

Username: root

Password: root