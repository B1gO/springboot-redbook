In this branch,
1. add new dependencies in pom.
```xml
<dependency>
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-validation</artifactId>
</dependency>
```

## Validation
add annotation for fields
* com.chuwa.redbook.payload.PostDto
* com.chuwa.redbook.payload.CommentDto
add @Valid for RequestBody in controller
* com.chuwa.redbook.controller.PostController
* com.chuwa.redbook.controller.CommentController


## acutator


## swagger


Please insert following records into `user_roles` tables before you sign up.
`insert into roles (name) values ("ROLE_USER");`
`insert into roles (name) values ("ROLE_ADMIN");`