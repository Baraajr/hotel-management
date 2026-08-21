# HotelAPI

A hotel management and booking REST API built with **NestJS, TypeScript, PostgreSQL, and Prisma**.

HotelAPI provides a backend system for managing hotels, rooms, users, and reservations with authentication, authorization, validation, and scalable modular architecture.

## Description

HotelAPI is a backend application designed to handle real-world hotel management workflows.

The API provides:

- User authentication and authorization
- Hotel management
- Room management
- Booking and reservation system
- User profiles
- Role-based access control
- Data validation
- Centralized error handling
- RESTful API architecture

The project follows NestJS best practices using modules, controllers, services, DTOs, guards, and dependency injection.

---

## Features

### Authentication

- JWT authentication
- User registration and login
- Password hashing
- Protected routes
- Role-based authorization
- Admin permissions

### Hotels

- Create hotels
- Update hotels
- Delete hotels
- View hotel details
- Manage hotel information

### Rooms

- Create and manage rooms
- Room pricing
- Room types
- Room capacity
- Room availability
- Hotel-room relationships

### Bookings

- Create reservations
- View booking history
- Manage bookings
- Validate booking dates
- Connect users with rooms

### API

- RESTful API design
- DTO validation
- Exception handling
- Modular architecture
- Environment-based configuration

---

## Project Structure

```text
src
│
├── auth
│   ├── controllers
│   ├── services
│   ├── guards
│   └── strategies
│
├── users
│   ├── controllers
│   ├── services
│   └── dto
│
├── hotels
│   ├── controllers
│   ├── services
│   └── dto
│
├── rooms
│   ├── controllers
│   ├── services
│   └── dto
│
├── bookings
│   ├── controllers
│   ├── services
│   └── dto
│
├── common
│   ├── filters
│   ├── guards
│   └── decorators
│
├── app.module.ts
└── main.ts
