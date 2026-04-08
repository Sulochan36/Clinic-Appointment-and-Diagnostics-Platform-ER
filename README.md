# 🏥 Clinic Management System – ER Diagram

This project presents an Entity-Relationship (ER) diagram for a modern clinic system designed to manage patients, doctors, appointments, consultations, diagnostic tests, reports, and payments.

---

## 📌 Overview

The system models a real-world clinic workflow where:

* Patients can book appointments with doctors
* Appointments may result in consultations (visits)
* Doctors can diagnose and prescribe diagnostic tests
* Tests generate reports at a later stage
* Payments are handled separately for consultations and diagnostics

---

## 🧠 Key Design Decisions

### Appointment vs Consultation

An appointment represents a scheduled booking, while a consultation represents the actual visit. Not all appointments result in consultations.

### Test Association

Diagnostic tests are linked to consultations, as they are prescribed by doctors after examining patients.

### Reports

Reports are generated for each prescribed test and linked accordingly.

### Doctor Specialization

Each doctor is associated with a single specialty to maintain focused expertise.

### Payments

Payments are handled separately for:

* Appointments (consultation fees)
* Prescribed tests (diagnostic fees)

---

## 🧩 Entities Included

* Patient
* Doctor
* Specialty
* Appointment
* Consultation
* Test
* PrescribedTest
* Report
* Payment

---

## 🔗 Relationships Covered

* A patient can book multiple appointments
* A doctor can attend multiple patients
* An appointment may or may not result in a consultation
* A consultation can have multiple prescribed tests
* Each prescribed test generates a report
* Payments are linked to appointments or prescribed tests

---

## 📁 ER Diagram

![Clinic Management System – ER Diagram](https://github.com/user-attachments/assets/c886798e-20b0-4b72-b95d-e7b74f2a0e65)

---

## 🎯 Objective

The goal of this design is to create a clean, scalable, and realistic database structure for a clinic system, focusing on clarity, proper relationships, and real-world workflow representation.

---

## 📚 Note

This project is part of a **Database Design Assignment** focused on understanding real-world system modeling using ER diagrams.
