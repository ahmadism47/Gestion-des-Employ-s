# Employee Manager Application

A full-stack web application for managing employee information with CRUD operations.

## Technologies Used

### Backend
- Spring Boot
- Spring Data JPA
- MySQL Database
- Maven

### Frontend
- Angular 19 (standalone components)
- TypeScript
- Bootstrap

## Features

- View all employees in a responsive grid layout
- Add new employees
- Edit existing employee information
- Delete employees
- Real-time updates

## The application will be available at `http://localhost:4200`

## API Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /employee/all | Get all employees |
| GET | /employee/find/{id} | Find employee by ID |
| POST | /employee/add | Add new employee |
| PUT | /employee/update | Update employee |
| DELETE | /employee/delete/{id} | Delete employee |

## Project Structure

### Backend
```
src/
├── main/
│   ├── java/
│   │   └── com/projet/employeemanager/
│   │       ├── model/
│   │       ├── repo/
│   │       ├── service/
│   │       └── exception/
│   └── resources/
│       └── application.properties
```

### Frontend
```
src/
├── app/
│   ├── employee.ts
│   ├── employee.service.ts
│   ├── app.component.ts
│   └── app.component.html
├── environments/
└── assets/
```

## Screenshot

![Employee Manager Interface](/api/placeholder/800/400)
