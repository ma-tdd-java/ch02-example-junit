

# Links:
- [Free Docker Desktop Alternative for Mac](https://medium.com/javarevisited/free-docker-desktop-alternative-for-mac-c3845d8a2345)
- [Could not find method compile() for arguments Gradle](https://stackoverflow.com/questions/23796404/could-not-find-method-compile-for-arguments-gradle)

# MongoDB

- Pull the MongoDB container:
  - docker pull mongo:latest
- Run the container.
  - docker run -d -p 27017:27017 --name mongoDB mongo:latest
- Restart container:
  - docker restart mongoDB
- Verify the state.
  - docker ps
- Access the MongoDB shell in the running container
  - docker exec -it mongoDB mongo