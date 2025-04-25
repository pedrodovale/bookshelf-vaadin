# Bookshelf

A Vaadin + SpringBoot + in-memory H2 DB application to keep track of books read by a user.

## How to deploy

> mvn spring-boot:run

The application main view is available at http://localhost:8080/books.

1. The application contains the list of read books (initially none):
![](var/img/screenshot1.png)

2. Once added with valid fields (form is validated):
![](var/img/screenshot2.png)

3. It is saved in the in-memory H2 DB and it visible in the read books list
![](var/img/screenshot3.png)

**By double-clicking a row, you can edit it** in the form.