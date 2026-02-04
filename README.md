<p align="center">
  <a href="https://nestjs.com/" target="_blank">
    <img src="https://nestjs.com/img/logo-small.svg" width="120" alt="NestJS Logo" />
  </a>
</p>

<p align="center">
  An Employee Management API built with <a href="https://nestjs.com/" target="_blank">NestJS</a>, showcasing authentication, CRUD operations, attendance management, and report generation.
</p>

---

## Project Description

This project is a simple **Employee Management API** designed to assess technical skills in **TypeScript, NestJS, testing, and code structure**.  

---

## Features

- **Authentication**
  - Register, Login, Logout
  - Forgot Password & Reset Password  
- **Employee Management (CRUD)**
  - Fields: `name`, `email`, `employeeIdentifier`, `phoneNumber`  
- **Attendance Management**
  - Record employee arrivals and departures  
  - Send email notifications when attendance is logged (via queues)  
- **Reports**
  - Generate daily attendance reports in **PDF** (`jsPDF`) and **Excel** (`excelJS`)  
- **API Documentation**
  - OpenAPI (Swagger) integration  

**Bonus Points**
- GitHub Actions to run all tests on PRs to `master` and `development` branches  

---

## Stack / Tools

- **Backend Framework**: NestJS v11  
- **Database**: MySQL (via TypeORM)  
- **Authentication**: PassportJS  
- **Testing**: Jest  
- **Reports**: jsPDF & excelJS  
- **Documentation**: OpenAPI (Swagger)  

---

## Getting Started

### Prerequisites

- Node.js >= 18
- npm >= 9
- MySQL database

---

### Installation

Clone the repository:

