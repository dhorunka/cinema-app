# Cinema-app 🎦
## Desciprion 🎥
This is simple cinema service. It supports CRUD operations, registration and authentication. It also allows you to make HTTP requests (GET, POST, PUT, DELETE).
You can add tickets, see available movie sessions and complete order.
## Features 🚀
*- registration/authentication*

*- choose admin/user role*

*- user can: register, get cinema-halls, get movies and available movie sessions, get shopping carts*

*- admin can: register, add cinema-halls, add movies and  update available movie sessions, add and delete shopping carts, get user by email*


## Project structure 📋
**This project has N-tier architecture**

*- DAO - all work with database is here*

*- Service - all business logic is here*

*- Controller - accept requests and sends responses to clients*

## Technologies 💡

*- Java 11*

*- Maven*

*- TomCat*

*- MYSQL*

*- Spring MVC*

*- REST*

*- Spring Security*

*- Hibernate*


## How to run this project 🔑
*- Fork this repo*

*- Copy link of project and create new project from VCS*

*- Edit ConnectionUtil db.properties file:*

```
    db.driver=YOUR_DRIVER
    db.url=YOUR_DATABASE_URL
    db.user=YOUR_LOGIN
    db.password=YOUR_PASSWORD

```
*- Install TomCat - https://tomcat.apache.org/download-90.cgi*

*- Configure TomCat in your IDE and run project*