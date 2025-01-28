# **DSList**

## Description
DSList is an API developed with Java Spring Boot that allows managing game lists, enabling the creation, listing, and organization of games into different categories. The project follows best practices in architecture, with well-defined layers and the use of modern technologies to ensure maintainability and scalability.

## Features

- **Game listing**: View a list of registered games.
- **Category organization**: Organize games into custom lists.
- **Game registration**: Add new games with detailed information.
- **Update and deletion**: Update or remove registered games.

## Conceptual model
![image](https://github.com/user-attachments/assets/e2e8d65f-3c88-463f-9b8b-b8acc481fde4)

## Project structure
![image](https://github.com/user-attachments/assets/64cccf5c-4664-481b-bb9b-a5a9d6f04e07)

## Technologies

- Java 21
- Spring Boot 3
- H2 Database (In-memory database for testing)
- JPA/Hibernate Object-relational mapping)
- Maven (Dependency management)
- Postman (HTTP methods testing for the controller)

## Endpoint functionality testing in Postman.

![image](https://github.com/user-attachments/assets/1f10314d-feae-4369-a1a0-7539dc84b9f8)
![image](https://github.com/user-attachments/assets/d67d08e3-f4b7-4db3-8c98-d2edd3ee636a)
![image](https://github.com/user-attachments/assets/b8718b27-9785-4be5-98b9-ecc80a4fbe36)
![image](https://github.com/user-attachments/assets/e3045c4f-8879-4ef1-880e-81f9de208ce1)
![image](https://github.com/user-attachments/assets/412547c2-527e-4775-aa94-58ac309d0d16)

## How to run

- Clone the repository:
git clone https://github.com/thiagodinho/dslist.git

- Navigate to the project folder:
cd dslist

- Run the project with Maven:
./mvnw spring-boot:run

Access the API:
The API will be available at: http://localhost:8080

## Acknowledgments  
A special thanks to Professor Nélio Alves and the DevSuperior team!





