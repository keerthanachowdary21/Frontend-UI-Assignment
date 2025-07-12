# Employee Directory Web Interface

## Overview
Responsive employee directory with CRUD operations, filtering, sorting, and pagination.

## Features
- Employee listing with pagination
- Add/edit employee forms with validation
- Search and filtering capabilities
- Responsive design for all devices

## Screenshots

### Dashboard View
![Dashboard](https://drive.google.com/uc?export=view&id=1KHrWtKW4pT9OEBRqL2q0tOmNgNLx9rHP)

### Filter Employees View
![Filter Employees](https://drive.google.com/uc?export=view&id=1BE3RcjDKUYmvB85e__2zctvsclOteSpl)

### Add Employee View
![Add Employee](https://drive.google.com/uc?export=view&id=1BjHn14PyauviTr6NGw4uI24l0lb7k0hH)

## Project Structure
- `/index.html`: Main dashboard
- `/styles.css`: Stylesheets
- `/script.js`: Main application logic

## Technical Implementation
- **Responsive Design**: Flexbox/Grid with media queries
- **Data Handling**: In-memory JavaScript array
- **Form Validation**: Client-side validation with error messaging
- **Pagination**: Configurable items per page (10, 25, 50)
- **Filtering**: Multi-criteria filtering by name/department/role
- **Sorting**: By first name or department

## Challenges & Improvements
**Challenges:**
1. Implementing pagination with dynamic filtering
2. Maintaining state between views without backend
3. Creating responsive card layout for various screen sizes

**Improvements:**
1. Add localStorage persistence for data
2. Implement advanced filtering options
3. Add employee photo upload capability
4. Improve accessibility (ARIA labels, contrast)
5. Add export to CSV functionality
