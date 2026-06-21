# Django JWT Authentication Learning Project

## Overview

This project is a hands-on implementation of JWT (JSON Web Token) Authentication using Django and Django REST Framework. The goal of this project was to understand how authentication works in modern web applications by building the complete authentication flow from scratch.

## Features Implemented

* User Registration API
* User Login API
* Password Hashing and Verification
* JWT Token Generation
* JWT Token Validation
* Protected User Endpoint
* Authentication using JWT
* HTTPOnly Cookie Storage
* User Logout Functionality
* Token Expiration Handling
* Custom User Model Integration
* Serializer Validation
* Django REST Framework APIViews

## JWT Concepts Learned

* What is JWT?
* JWT Structure (Header, Payload, Signature)
* Authentication vs Authorization
* Stateless Authentication
* Token Encoding and Decoding
* Secret Key Usage
* Expiration Claims (`exp`)
* Issued At Claims (`iat`)
* Cookie-Based Authentication
* Protected Routes
* Authentication Error Handling

## Tech Stack

* Python
* Django
* Django REST Framework
* PyJWT
* SQLite

## API Endpoints

| Method | Endpoint      | Description                 |
| ------ | ------------- | --------------------------- |
| POST   | /api/register | Register a new user         |
| POST   | /api/login    | Login user and generate JWT |
| GET    | /api/user     | Retrieve authenticated user |
| POST   | /api/logout   | Logout user                 |

## Future Improvements

* Refresh Tokens
* Access Token & Refresh Token Architecture
* Role-Based Authorization
* Permission Classes
* Bearer Token Authentication
* React Frontend Integration
* Django Simple JWT
* Token Blacklisting
* Secure Cookie Configuration
* Production Deployment Best Practices

## Learning Outcome

Through this project, I gained practical experience with JWT authentication, cookie-based authentication, Django REST Framework, API security fundamentals, and building protected REST APIs from scratch.
