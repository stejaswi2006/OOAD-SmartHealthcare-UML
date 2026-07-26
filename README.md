# OOAD UML Diagrams

## Repository Description

This repository contains UML diagrams created for the Object-Oriented Analysis and Design (OOAD) course using Umbrello UML Modeller.

Projects included:
- Smart Healthcare System
- University Management System
## Tool Used
- Umbrello UML Modeller

## Files
- SmartHealthcare.xmi – Umbrello project file
- ClassDiagram.png – UML Class Diagram

## Classes
- Person
- Doctor
- Patient
- Appointment
- Medical Record
- Prescription
- Hospital

## Relationships
- Association
- Aggregation
- Composition

## Author

Tejaswi Srinivasa Kumar

---

# University Management System

## Project Title
Modeling Object Relationships in a University Management System

## Tool Used
- Umbrello UML Modeller

## Files
- UniversityManagement.xmi – Umbrello project file
- UniversityManagement.png – UML Class Diagram

## Classes
- Student
- Faculty
- Department
- Course

## Relationships
- Association
- Aggregation
- Composition

## Multiplicities
- Department (1) ◇── (*) Faculty
- Department (1) ◆── (*) Course
- Faculty (1) ── (*) Course
- Student (*) ── (*) Course
---

# Smart Hotel Reservation System

## Project Title
Modeling Guest Reservation and Hotel Management Using a Use Case Diagram

## Tool Used
- Umbrello UML Modeller

## Files
- SmartHotelReservation.xmi – Umbrello project file
- SmartHotelReservation.png – UML Use Case Diagram

## Actors
- Guest
- Registered Guest
- Receptionist
- Manager
- Payment Service

## Use Cases
- Search Rooms
- View Room Availability
- Make Reservation
- Cancel Booking
- Make Payment
- Receive Booking Confirmation
- Allocate Rooms
- Generate Reports
- Manage Reservations
- Check-in Guest
- Check-out Guest
- Process Payment

## Relationships
- Association
- Include
- Extend
- Generalization

---

# University Management System (Enhanced)

## Project Title
Designing a University Management System Using a Class Diagram

## Tool Used
- Umbrello UML Modeller

## Files
- UniversityManagementClass.xmi – Umbrello project file
- UniversityManagementClass.png – UML Class Diagram

## Classes
- Person
- Student
- Faculty
- Department
- Course
- Examination

## Relationships
- Generalization (Inheritance)
- Association
- Aggregation

## Multiplicities
- Student (*) ── (*) Course
- Student (1) ── (*) Examination
- Department (1) ◇── (*) Faculty
- Department (1) ◇── (*) Course
- Faculty (1) ── (*) Course
