# LoginPage

This project was generated with Angular to create a front end for [Backend API with JWT Authentication](https://github.com/jaum-fs/login-page-backend)

## Development server

To test signin ande signup pages, clone the project.
Tools to run project: node, angular 17 and ngx-toastr
After install this itens, start project with node package manager

`npm start`

## Endpoints 

| METHOD | ENDPOINT | DESCRIPTION | REQUEST EXAMPLE | RESPONSE EXAMPLE |
|---|---|---|---|---|
| GET | `/user` | Return a page when user has a token | `curl -X GET "https://localhost:4200/user"`
| POST | `/login` | Signin page | `curl -X POST -H "Content-Type: application/json" -d '{"email": "test@gmail.com", "password":"teste123"}' "http://localhost:4200/auth/login"` | `{"name": "xpto", "token":"xpto"}` |
| POST | `/register` | Signup page | `curl -X POST -H "Content-Type: application/json" -d '{"name":"John","email": "test@gmail.com", "password":"teste123"}' "http://localhost:4200/auth/register"` | `{"name": "John", "token":"xpto"}` |



