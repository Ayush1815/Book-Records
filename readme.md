
**Bookstore Management System**
A RESTful Spring Boot application for managing bookstore records with full CRUD operations and search functionality.

*📚 Project Overview*
This is a backend API for a bookstore management system that allows you to manage book records, search books by various criteria, and perform standard CRUD operations.

*🚀 Features*
CRUD Operations: Create, Read, Update, and Delete book records

Advanced Search: Find books by ID, author, title, or price

RESTful API: Clean and intuitive REST endpoints

JPA/Hibernate: Database persistence with Spring Data JPA

Lombok Support: Reduced boilerplate code with annotations

Serializable Entities: Support for object serialization

*🛠️ Technologies Used*
Java 17+

Spring Boot 3.x

Spring Data JPA

Hibernate

Lombok

Maven/Gradle (depending on project setup)

Database: MySQL/PostgreSQL/H2 (configurable)

*📁 Project Structure*
text
src/main/java/com/record/books/
├── Controller/           # REST Controllers
│   └── Controller.java   # Main controller with all endpoints
├── Service/             # Business logic layer
│   └── BookService.java # Book service interface
├── entities/            # JPA Entities
│   └── Books.java       # Book entity class
└── repository/          # Data access layer (not shown but assumed)
    └── BookRepository.java

*📝 Sample Requests*

1. Add a New Book
POST /test/post/postbooks

2. Update a Book
PUT /test/update/putBooks/1

3. Search by Author
GET /test/getBooksByAuthor/F. Scott Fitzgerald

4. Search by Price
GET /test/getBookByPrice/12.99

*🚦 Getting Started*

Prerequisites
Java 17 or higher

Maven or Gradle

IDE (IntelliJ IDEA, Eclipse, or VS Code)

Database (MySQL, PostgreSQL, or H2)

*Installation Steps*

Clone the repository

bash
git clone <repository-url>
cd <project-directory>