
<h1 align="center">Workshop MongoDB</h1> <p align="center"> <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/workshop-mongodb?color=56BEB8"> <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/workshop-mongodb?color=56BEB8"> <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/workshop-mongodb?color=56BEB8"> </p> <p align="center"> <a href="#dart-about">About</a> &#xa0; | &#xa0; <a href="#memo-project-structure">Project Structure</a> &#xa0; | &#xa0; <a href="#sparkles-features">Features</a> &#xa0; | &#xa0; <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0; <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0; <a href="#checkered_flag-execution">Execution</a> &#xa0; | &#xa0; <a href="#memo-license">License</a> &#xa0; | &#xa0; <a href="https://github.com/gsoaresdz" target="_blank">Author</a> </p> <br>

## **:dart: About**

This project is part of the DevSuperior MongoDB workshop, covering fundamental concepts of NoSQL databases using Spring Boot and MongoDB.

The system simulates a basic social network, allowing users to make posts and comment on other users' posts.

## **:memo: Project Structure**

The project follows an MVC (Model-View-Controller) architecture and includes the following components:

- **Models**: Representation of Users and Posts with embedded relationships in MongoDB.
- **Repositories**: Interfaces for database communication using MongoDB.
- **Services**: Business logic and data manipulation.
- **Controllers**: REST endpoints for system interaction.

## **:sparkles: Features**

:heavy_check_mark: **User Registration**: Register new users.

:heavy_check_mark: **Post Creation**: Users can create posts.

:heavy_check_mark: **Commenting on Posts**: Users can comment on posts.

:heavy_check_mark: **Search Posts by Text**: Search functionality for posts.

## **:rocket: Technologies**

### **Backend**

- Java
- Spring Boot
- MongoDB
- Spring Data MongoDB
- Maven

## **:white_check_mark: Requirements**

- Java 11+
- MongoDB installed

## **:checkered_flag: Execution**

### **Backend**

```
# Clone the repository
$ git clone https://github.com/gsoaresdz/workshop-mongodb.git

# Navigate to the project folder
$ cd workshop-mongodb

# Run the project
$ ./mvnw spring-boot:run
```

## **:memo: License**

This project is under the MIT license. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>
