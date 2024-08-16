# Assignment

## Introduction
In this assignment, you are required to create a web or mobile page with the following functionalities

## Objectives

- Learn how to manage UI
- Practice skills in handling asynchronous operations with JavaScript

  
> [!IMPORTANT]
> Web Required to use the React.js or Next.js frameworks for this project.
> 
> Mobile Required to use the React Native or Flutter frameworks for this project.

## Assignment Description

### Example JSON

```json
[
    {
        "id": 1,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    },
    {
        "id": 2,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    },
    {
        "id": 3,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    },
    {
        "id": 4,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    },
    {
        "id": 5,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    },
    {
        "id": 6,
        "username": "********",
        "email": "********@********.com",
        "first_name": "********",
        "last_name": "********",
        "is_active": true,
        "date_joined": "2024-08-09T18:01:17.988250+07:00"
    }
]
```
### 1. User management list

Please make a todo list that
- Create a login system
- Develop a user list page to display users
- Allows adding, editing, and deleting user information
  
> [!CAUTION]
> Please do your best to show your best solution we are looking for
> - Answer the need of question
> - Clean code easy to read
> - Bonus: if you have multiple solutions we could discuss those theories in our interview (no need to submit multiple versions, just send us the best one you think.)

### 2. Functions Call API (OPTIONAL)

- Your project must use Typescript, Typescript module, and HTTP framework
- We encourage you to write tests, which we will give you some extra score
- We will give you an extra score if you focus on performance.
- All API sample (included CURD operation for User object) can be found in Postman collection and environment JSON file in this repository.

> [!TIP]
> Bonus points will be awarded for utilizing environment variables (ENV).

### Sample REST API
- #### Login Create Token

  API from <http://iottechgroup.dyndns.biz:18180/api/token/>
  
  Method : POST

  json-body:
  ```json
  {
    "username": "user1",
    "password": "user1@project"
  }
  ```
- #### Refresh Token

  API from <http://iottechgroup.dyndns.biz:18180/api/token/refresh/>
  
  Method : POST
  
  json-body:
  ```json
  {
    "refresh": "xxxx",
  }
  ```

