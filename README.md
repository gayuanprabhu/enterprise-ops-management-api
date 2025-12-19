# Enterprise Operations Management System (EOMS)

## Overview
Enterprise Operations Management System is a backend-focused REST API designed to handle internal organizational workflows such as service ticket management and expense reimbursement.

The system is built using Node.js and MySQL, with JWT-based authentication and role-based access control.

## Tech Stack
- Backend: Node.js, Express
- Database: MySQL
- Authentication: JWT
- API Testing: Postman

## Core Features
- User registration and login
- JWT-based authentication
- Role-based access (Admin, Manager, Employee)
- Modular architecture for multiple enterprise workflows

## Modules
### 1. Service Ticket Management
- Create and track service requests
- Update ticket status
- Maintain ticket logs

### 2. Expense & Reimbursement
- Submit expenses
- Manager approval flow
- Expense history tracking

## Database Design
- Users
- Tickets
- Ticket Logs
- Expenses
- Expense Logs

## API Flow
1. User signs up and logs in
2. JWT token is issued
3. Protected APIs accessed using token
4. Data stored and managed in MySQL

## How to Run
1. Clone the repository
2. Install dependencies
3. Configure `.env`
4. Start server


## Future Enhancements
- Swagger API documentation
- Admin dashboard
- Advanced reporting

## Author
Gayatri Anil Prabhu
