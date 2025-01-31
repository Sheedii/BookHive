# BookHive

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
  - [Class Diagram](#class-diagram)
  - [Security Diagram](#security-diagram)
- [Technologies Used](#technologies-used)
  - [Backend (BookHive)](#backend-bookhive)
  - [Frontend (BookHive-ui)](#frontend-bookhive-ui)
- [Acknowledgments](#acknowledgments)

## Overview

**BookHive** is a full-stack application designed for book enthusiasts to manage their collections and engage with a like-minded community. It provides user registration, secure authentication, and email validation while enabling seamless book management. Users can add, update, share, and archive books, as well as borrow and return them with an approval process for returns. The application ensures security using JWT authentication and follows best practices in REST API design.

- **Backend:** Spring Boot 3 & Spring Security 6
- **Frontend:** Angular with Bootstrap for styling

## Features

- **User Registration & Authentication:** Secure account creation, login, and email validation.
- **Book Management:** Users can add, update, share, and archive books.
- **Book Borrowing System:** Availability checks before borrowing a book.
- **Book Return Workflow:** Users can return books, with an approval process for return confirmations.
- **Secure API:** Implements JWT authentication for secure access.

## Architecture

### Class Diagram
![Class diagram](images/class-diagram.png)

### Security Diagram
![Security diagram](images/security.png)

## Technologies Used

### Backend (BookHive)
- Spring Boot 3
- Spring Security 6
- JWT Token Authentication
- Spring Data JPA
- Docker

### Frontend (BookHive-ui) *(In Progress)*
- Angular
- Component-Based Architecture
- Bootstrap for UI Styling

## Acknowledgments

Special thanks to the developers and maintainers of the open-source technologies used in this project. Their contributions make applications like **BookHive** possible.
