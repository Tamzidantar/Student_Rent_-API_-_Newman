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

## Newman and Report Installation Process :
- Newman Install command :
```http
  npm install -g newman-reporter-htmlextra
```
- Newman Htlm Report Install Command :
```http
  npm install -g newman-reporter-html
```
## API Documentation :
```http
https://documenter.getpostman.com/view/38560436/2sAY4sijCb
```
### Test case list :
  1. Get Student
   - a test case for Status Code Validation
   -  Check the length of the response.


