![Java](https://img.shields.io/badge/Java-FEB95F?style=for-the-badge&logo=java&logoColor=white)
![Spring-Boot](https://img.shields.io/badge/SpringBoot-81FF5E?style=for-the-badge&logo=spring&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-38B000?style=for-the-badge&logo=MongoDb&logoColor=white)
![ReactJs](https://img.shields.io/badge/rEACTjs-0fa3b1?style=for-the-badge&logo=React&logoColor=white)

# A memories persisted application
- A simple memories and moments storage app where users can login and upload images, tags and captions for their memories.
- Search for memories by tags.
- Upload and delete the memories

# Overview
- I use java spring boot and mongodb database to serve the react frontend

# Requirements

- Java 17 or later
- MongoDb database running on port 27017

# Set-up

- Clone the repository:
 
         

            git clone https://github.com/yourusername/Memories-Persisted-App.git


- **NB** make sure no application is running on port 8080 and 3000 otherwise change port before running the application
            

            cd Memories-Persisted-App/javaBackend/javabackend
            mvnw clean package
           
- The server will start at http://localhost:8080
         

            cd Memories-Persisted-App/client
            npm install
            npm start

- The ui will start at http://localhost:3000

# Features
Rental-Units-Management-System provides the following features:

* Create, edit and delete memories.
* Add tags and images to the memory
* Search by tag


# License
 Licensed under the MIT License.
