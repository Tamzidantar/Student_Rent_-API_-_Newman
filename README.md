# Student_Rest API_Newman

## How to run this project



- Clone this Project
- Open with Postman/Command shell
- Run command:

```http
  newman run Student_Rest_API.postman_collection.json -e Student_Rest_API.postman_environment.json
```
- Run Command for Report (Newman) :
```http
 newman run Student_Rest_API.postman_collection.json -e Student_Rest_API.postman_environment.json -r cli,htmlextra
```

## Technology used :
- Postman
- Newman

## Prerequisite :
- Jdk
- Node Js 
- Newman
- Html Report Library
