# Final Exam - Section 2
## Objective: 
1. Improve test coverage and achieve at least 80% test coverage
2. Dockerize the app (No need to write github action or push to Docker hub, just write the dockerfile and test it locally, then push the file here)

Note: You can directly work on the main branch

### How to run the app locally
To run locally you need to be sure that the dependencies are installed:
```
$ npm install
```
To run:
```
$ npm start
```

### How to test the app

```
$ npm test
```


### How to run code coverage

```
$ npm run test-coverage
```
Note the duplicate --. 
The first separates the parameters passed to the npm command itself and the following are passed to the test script.


# How to test docker

## Build the docker file

```
docker build -t <image_name>:<tag_name>
```

## Run the docker command

```
docker run -it <image_name>:<tag_name>
```

# Deliverables

1. Test coverage atleast 80%
2. Working Dockerfile
