📚 ALX Airbnb Clone Project Documentation Repository

This repository serves as the central documentation hub for the backend architecture and system design of the Airbnb Clone project. The documents here follow a structured approach to defining requirements, system interactions, and data modeling prior to implementation.

📁 Key Documentation Artifacts

Document

Filepath

Description

Project Readme

README.md

Overview of the project, objectives, and structure of the repository.

Features and Functionalities

features-and-functionalities/features-and-functionalities.md

Detailed list of all backend features, covering user management, listings, booking, and payments.

Use Case Diagram Documentation

use-case-diagram/use-case-diagram.md

Definition of all primary actors and system use cases, providing the blueprint for the visual use case diagram.

Database Schema (3NF)

schema.sql (In previous phase)

Definition of the normalized relational database tables (3NF) for core entities.

Reporting Queries

reporting_queries.sql (In previous phase)

Sample SQL queries demonstrating how to extract meaningful data from the normalized schema.

📐 Use Case Diagram Summary

The use-case-diagram/use-case-diagram.md file defines the following core actors and their primary interactions with the system:

Actor

Key Interactions

Guest

Register, Log In, Search/Filter Properties, Create Booking, Cancel Booking, Submit Review, Process Payment.

Host

Register, Log In, Create/Manage Property Listing, View Bookings Received, View Payouts.

System

Handles all logic, authentication, data persistence, and core business rules.

Payment Gateway

Handles secure Process Payment transactions (external to the primary system boundary).

The diagram's relationships include:

Create Booking includes Check Availability.

Submit Review & Rating extends the completed booking process.

✅ Completion Status

All documented artifacts lay the groundwork for the development of the robust and scalable Airbnb Clone backend.
