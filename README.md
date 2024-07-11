# Book Social Network

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
  - [Backend (book-social-network)](#backend-book-social-network)
  - [Frontend (book-social-network-ui)](#frontend-book-social-network-ui)
- [Getting Started](#getting-started)

## Overview

Book Social Network is a comprehensive application allowing users to oversee their personal book libraries and connect with fellow book lovers. Key features include user sign-up, secure email confirmation, and extensive book management capabilities such as adding, updating, sharing, and archiving books. Users can also borrow and return books with availability checks and return approval processes. Security is maintained through JWT tokens, following industry best practices for REST API design. The backend utilizes Spring Boot 3 and Spring Security 6, while the frontend is crafted with Angular and styled using Bootstrap.

## Features

- Account Creation: Users have the option to sign up for a new account.
- Email Verification: Accounts are confirmed through secure email verification codes.
- User Login: Existing users can securely access their accounts.
- Book Handling: Users can add, modify, share, and archive their books.
- Borrowing Process: Ensures that all conditions for borrowing a book are met.
- Returning Books: Users can return the books they have borrowed.
- Return Approval: Provides the ability to approve the return of books.

## Technologies Used

### Backend (book-network)

- Spring Boot 3
- Spring Security 6
- JWT Token Authentication
- Spring Data JPA
- JSR-303 and Spring Validation
- OpenAPI and Swagger UI Documentation
- Docker
- GitHub Actions
- Keycloak

### Frontend (book-network-ui)

- Angular
- Component-Based Architecture
- Lazy Loading
- Authentication Guard
- OpenAPI Generator for Angular
- Bootstrap

## Getting Started

To get started with the Book Social Network project, follow the setup instructions in the respective directories:

- [Backend Setup Instructions](/book-network/README.md)
- [Frontend Setup Instructions](book-network-ui/README.md)
