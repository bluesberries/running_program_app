# Running Program

Build a simple web app to view the [running program](https://www.halhigdon.com/training-programs/marathon-training/novice-1-marathon/).

## Motivation
My goal is to build a basic full stack application to become familiar with web development.

## To run
### With Docker
```
docker build -t my-node-app .
docker run -p 3000:3000 my-node-app 
```
### Directly with Node
```
node app.js
```

## Approach
1. Build the backend service to read from an excel file
2. Add the REST APIs
3. Replace the excel file with a database
4. Build the front-end

## Ideas for further enhancements
- Import other running programs for different distances / levels.
