# Spring boot articles crud

Simple crud for handling and administration of articles with database and all the services of the CRUD concept.

Using Maven Command: Download the project source code. Go to the root folder of the project using command prompt and run the command.
`mvn spring-boot:run`

### methods of use [you can use Postman to try it]

1. Create :
HTTP Method: POST, URL: /user/article
```
POST - http://localhost:8080/user/article
```

2. Read :
HTTP Method: GET, URL: /user/article/{id}
HTTP Method: GET, URL: /user/articles
```
GET -  http://localhost:8080/user/article/2
GET -  http://localhost:8080/user/articles
```

3. Update :
HTTP Method: PUT, URL: /user/article
```
PUT - http://localhost:8080/user/article
```

4. Delete :
HTTP Method: DELETE, URL: /user/article/{id}
```
DELETE  - http://localhost:8080/user/article/3
```


