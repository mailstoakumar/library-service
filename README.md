# Library Service

A simple RESTful service built with Spring Boot for managing a library's books. This service allows you to perform basic CRUD operations on a collection of books.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Building and Running](#building-and-running)
- [API Endpoints](#api-endpoints)
- [H2 Database Console](#h2-database-console)
- [Contributing](#contributing)
- [License](#license)

## Features
- Create, Read, Update, and Delete (CRUD) books in the library.
- In-memory H2 database for data persistence.
- RESTful endpoints for managing books.
- Easily configurable via `application.properties`.

## Technologies Used
- **Java**: 17 (or specify the version you are using)
- **Spring Boot**: 3.x.x (or your version)
- **H2 Database**: In-memory database for quick testing and development.
- **Maven**: For build and dependency management.

## Api Endpoints
GET http://localhost:9090/api/books
POST http://localhost:9090/api/books
   e.g. {
         "title": "Effective Java",
         "author": "Joshua Bloch",
         "isbn": "9780134685991",
         "publishedYear": 2018
        }

PUT http://localhost:9090/api/books/2
    e.g. {
            "title": "Effective Java - 3rd Edition",
            "author": "Joshua Bloch",
            "isbn": "9780134685991",
            "publishedYear": 2018
         }

## Getting Started
To get a local copy of the project up and running, follow these steps.

### Prerequisites
- **Java JDK 17** or higher
- **Maven**: For building the project
- **Git**: For cloning the repository

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mailstoakumar/library-service.git


