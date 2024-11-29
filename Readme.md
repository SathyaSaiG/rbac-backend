# Role-Based Access Control (RBAC) System

## Overview
This is a simple Role-Based Access Control system built with Spring Boot, providing secure user authentication and authorization.

## Features
- User Registration
- JWT-based Authentication
- Role-Based Access Control
- Secure Password Handling

## Prerequisites
- Java 21
- MySQL
- Maven

## Setup
1. Create MySQL database:
   ```sql
   CREATE DATABASE rbac;
   ```

2. Update `application.properties` with your MySQL credentials

3. Run the application:
   ```
   mvn spring-boot:run
   ```

## Endpoints
- `/api/auth/register`: Register new user
- `/api/auth/login`: User login
- `/api/admin/`: Admin-only endpoints
- `/api/user/`: User-level endpoints

## Default Roles
- ADMIN
- USER

## Security Measures
- BCrypt Password Encoding
- JWT Token Authentication
- Role-Based Endpoint Access
