#  Management And Product Ordering System

This project is a simple inventory and purchasing management system designed to manage product stock, handle item ordering, and provide prediction services for inventory management.

The system consists of multiple mobile applications and backend services working together.

## Tech Stack

* **Mobile Apps**: Flutter (GetX State Management)
* **Backend API**: Laravel
* **Prediction Service**: FastAPI
* **Database**: MySQL

## Repository Structure

This repository contains five main components:

1. **App-Kelola-Stok**
   A Flutter mobile application used to manage product inventory and monitor stock levels.
   This application uses **GetX** for state management, dependency injection, and route management.

2. **App-Pesan-Barang**
   A Flutter mobile application used to create and manage purchase orders for restocking items.
   It also uses **GetX** to manage application state and navigation.

3. **Backend Model Prediksi**
   A backend service built with **FastAPI** used to run prediction models related to inventory or demand forecasting.

4. **Backend Sistem Pulau Baru**
   The main backend service built with **Laravel**, responsible for handling API requests, business logic, and communication with the database.

5. **Database**
   Contains the SQL schema that can be imported into **MySQL**.

## System Architecture

The system architecture consists of the following components:

* **Flutter Applications** communicate with the **Laravel Backend API**
* The **Laravel backend** handles business logic and database operations
* The **FastAPI service** is used for prediction or analytics features
* All application data is stored in **MySQL**

## Database

The database schema is located in:

```
Database/schema.sql
```

Import this file into your MySQL server before running the application.

## Notes

This project was developed as a learning project focused on integrating mobile applications, backend APIs, and prediction services into a single system.
