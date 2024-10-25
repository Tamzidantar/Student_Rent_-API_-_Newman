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
 #### 1. Get Student
  in the test case you need to validate the following field values.
#### verify Get Student Details
  - Status Code 200 Validation
  - Array length output in console
#### 2. Create Student
  Create data stes using the Dynamic Random Variables. in the test case you need to validate the following field values.
  - Status Code 201 Validation
#### 3. Get Specific Student
  Create data stes using the Dynamic Random Variables.
#### verify Get Specific Student Details
 in the test case you need to validate the following field values.
 - ID
 - First Name
 - Middle Name
 - Last Name
 - Date of Birth
#### 4. Create Technical Skills
  Create data stes using the Dynamic Random Variables. in the test case you need to validate the following field values.
  - a test case for Status Code 200 Validation.
#### 5. Create Student Address
Create data stes using the Dynamic Random Variables. in the test case you need to validate the following field values.
  -  a test case for Status Code 200 Validation.
  - a test case for status and message field value validation.
#### 6. Final Student Detatlis
  in the test case you need to validate the following field values.
#### verify Final Student Details 
   - Status Code Validation 
   - Language
   - Year of Experience
   - House Number
   - City
   - Country
   - Mobile
   - Current Address
### Newman Report Summary :
![Screenshot_13](https://github.com/user-attachments/assets/a066a820-1e48-488a-acc1-c285f950f45b)
![Screenshot_15](https://github.com/user-attachments/assets/a50c4046-2ca5-4e69-8676-1ded9a85d82f)
![Screenshot_16](https://github.com/user-attachments/assets/3c43848e-3eb4-45eb-a531-15a881bfb5e6)
![Screenshot_17](https://github.com/user-attachments/assets/e3bd78eb-6019-4e57-b3b7-147d67d1317d)





   




