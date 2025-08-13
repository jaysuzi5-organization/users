# Documentation for users
### fastAPI: API that is responsible for managing users


Test: Users (should be capitalized)


This application has two generic endpoints:

| Method | URL Pattern           | Description             |
|--------|-----------------------|--------------------|
| GET    | /api/v1/users/info         | Basic description of the application and container     |
| GET    | /api/v1/users/health    | Health check endpoint     |



## CRUD Endpoints:
| Method | URL Pattern           | Description             | Example             |
|--------|-----------------------|--------------------|---------------------|
| GET    | /api/v1/users         | List all users     | /api/v1/users       |
| GET    | /api/v1/users/{id}    | Get users by ID     | /api/v1/users/42    |
| POST   | /api/v1/users         | Create new users    | /api/v1/users       |
| PUT    | /api/v1/users/{id}    | Update users (full) | /api/v1/users/42    |
| PATCH  | /api/v1/users/{id}    | Update users (partial) | /api/v1/users/42 |
| DELETE | /api/v1/users/{id}    | Delete users        | /api/v1/users/42    |


### Access the info endpoint
http://home.dev.com/api/v1/users/info

### View test page
http://home.dev.com/users/test/users.html

### Swagger:
http://home.dev.com/api/v1/users/docs