# Vision Document

This document presents an overview of the **Appointment Management System**, describing its purpose, target audience, problems addressed, and key requirements guiding development.

## 1. Executive Summary
The system is a **platform for appointment management** targeting small businesses and independent professionals.  
It helps to:

- Organize service schedules  
- Record completed services  
- Track earnings over time  
- Apply **penalty policies** for client no-shows or late arrivals  

---

## 2. Target Audience
Intended for **self-employed professionals** and **small to medium businesses** that rely on appointments.  

Main users:

- Beauty salons and aesthetics centers  
- Barber shops  
- Tattoo studios  
- Clinics and private offices  
- Personal trainers  
- Photographers  

---

## 3. Problems Addressed
Common challenges for small service-based businesses:

- **Scheduling conflicts** due to manual organization  
- **Client no-shows or delays**  
- **Difficulty tracking earnings** and financial performance  
- **Last-minute cancellations**, causing lost time  

---

## 4. Scope

### 4.1 What the system is
- Appointment management and automation  
- Earnings tracking per service  
- Penalty application for late or absent clients  
- Financial history recording and consultation  

### 4.2 What the system is not
- Personal task manager  
- Full accounting system  
- Digital wallet  
- Automatic billing or banking integrations  
- Service rating or review system  
- Employee management system (payroll, HR)  

### 4.3 Key Features
- Register services (name, price, duration)  
- Schedule, reschedule, and cancel appointments  
- Apply penalty policies  
- Track earnings and financial history  
- Role-based access control  

---

## 5. Users

- **Employees:** schedule and consult appointments  
- **Clients:** view services and book appointments  
- **Independent Professionals:** track their schedule, record services, check earnings  
- **Business Owners:** monitor financial history and appointments of multiple employees  

---

## 6. Functional Requirements

### 6.1 User Management
- Register companies and users  
- Self-registration for users  
- Individual login  
- Role definition: client, employee, independent, business owner  
- Register company employees  

### 6.2 Services
- Register and configure service types (price, duration)  
- Associate services with employees  

### 6.3 Scheduling
- Client and employee booking  
- Cancellation and rescheduling  
- Prevent double-booking and conflicts  
- Show available times per employee  
- Configure company operating hours  
- Notify clients of appointments  
- Apply rules for maximum delay and penalties  

### 6.4 Financial Tracking
- Record completed services  
- Update financial history (daily, weekly, monthly)  
- Provide access to company owners  

---

## 7. Non-Functional Requirements

- **Performance:** respond within 2 seconds, support 100+ simultaneous bookings, 99% uptime  
- **Usability:** easy navigation, responsive layout, beginner-friendly  
- **Security:** secure login, encrypted data, operation logs, data isolation  
- **Compatibility:** Chrome, Edge, Firefox  
- **Reliability:** ensure data consistency, provide backup and recovery  

---

## 8. Requirements Traceability

- **Scheduling:** RF10–RF19  
- **No-shows & Delays:** RF20–RF26  
- **Financial Tracking:** RF29–RF32  
- **User Management:** RF01–RF06  
- **Service Management:** RF07–RF09  

---

## 9. System Usage

- Web-based, accessible on desktop, tablet, and mobile  
- Each business has isolated users, clients, services, and records  
- Typical workflow: register → configure → employees/clients schedule → system enforces rules  

---

## 10. Glossary

- **Profile:** user role and permissions  
- **Penalty Policy:** rules for client no-shows or late arrivals  
- **Service:** schedulable and chargeable business activity  
- **Financial History:** records of services and earnings, by period  
- **Company:** organization or professional using the system