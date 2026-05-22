# Relationship Manager Component (`relationshipmgr`)

A custom Moqui component built to manage Party and Contact Mechanism relationships using Mantle UDM concepts.

---

## 🏗️ Architecture & Data Modeling

This component implements core enterprise data modeling concepts:

### Supertype / Subtype Modeling

- `Party` (Supertype)
  - `Person`
  - `Organization`

- `ContactMech` (Supertype)
  - `PostalAddress`
  - `TelecomNumber`
  - `EmailAddress`

### Association / Intersection Entities

- `PartyRole`
  - Handles Party ↔ Role relationships

- `PartyContactMech`
  - Handles Party ↔ Contact Mechanism relationships

### Data Classifications

Used classification entities for:

- Party Types
- Role Types
- Contact Mechanism Types
- Contact Purposes

---

## ⚙️ Backend Implementation

Implemented entity relationships and CRUD operations using:

- XML Entity Definitions
- Services
- Forms and Screens

The application manages:

- Party creation
- Role assignment
- Contact management
- Address management

---

## 🖥️ UI / UX

Built UI screens and forms for:

- Persons
- Organizations
- Roles
- Contact Mechanisms

Features include:

- Create
- View
- Update
- Delete operations

---

## 🧪 Sample Data

### Organizations
- ABC Engineering College
- Computer Science Department

### Persons
- Adarsh Goyal
- Rahul Sharma
- Dr. Amit Verma

### Roles
- Student
- Teacher
- Department

---

## 🛠️ Technologies Used

- Moqui Framework
- Mantle UDM
- XML Entity Definitions
- XML Forms and Screens

---
