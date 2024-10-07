# Airline Booking System (ABS)  
**Version**: 1.0.0  
**Date**: 09/20/2024  

**Authors**:  
- Danrell Rodriguez  
- Lucky Gaguin  
- Mary Grace Isonza  
- Ryan Bardahi  
- Sarah Santos  

---

## Table of Contents  
1. [Introduction](#3-introduction)  
2. [Overall Description](#4-overall-description)  
3. [Visual Mockup Reference](#5-visual-mockup-reference)  
4. [Features](#6-features)  
5. [Functional Requirements](#7-functional-requirements)  
6. [Non-Functional Requirements](#8-non-functional-requirements)  
7. [Data Requirements](#9-data-requirements)  
8. [External Interface Requirements](#10-external-interface-requirements)  
9. [Glossary](#11-glossary)  
10. [Appendices](#12-appendices)  

---

## 3. Introduction  

The **Airline Booking System (ABS)** is a web-based application designed to streamline the process of searching, selecting, and booking flights for travelers. It allows users to perform tasks such as flight searches, booking confirmations, profile management, and more, offering a seamless experience for customers and administrators alike.  

The ABS system focuses on creating an intuitive, efficient, and secure platform for travelers, providing all necessary functionalities from initial flight search to post-booking itinerary management.

---

## 4. Overall Description  

The Airline Booking System is designed with the following core functionalities:  
- A **Landing Section** to greet and engage users.  
- A **Flight Search System** that allows users to find flights based on criteria such as destination, date, and seat class.  
- **Booking Confirmation** to finalize reservations and receive booking details.  
- **User Management** features, including **Login/Logout**, **Registration**, and **Profile Management** for a personalized experience.  
- An **Itinerary Details** page for reviewing booked flights.  
- An **About Page** that explains the system and the airline’s mission.  

Technologies used include HTML, CSS, JavaScript, Node.js, MongoDB for storing flight and user data.

---

## 5. Visual Mockup Reference  

The mockup consists of the following key sections:  
- **Landing Page** with quick access to flight search.  
- **Flight Search Results Page** that displays flight options.  
- **Booking Confirmation Page** with a summary of selected flights.  
- **Login/Registration Page** with fields for user input.  
- **User Profile Page** where customers can manage their details and itineraries.  
*Mockups will be included in the appendices.*

---

## 6. Features  

1. **Landing Section**  
   - A welcome screen providing quick access to the flight search and a brief introduction to the service.  
   
2. **Flight Search Results**  
   - Displays a list of flights based on user-specified search criteria such as departure and destination cities, travel dates, number of passengers, and cabin class.  
   
3. **Booking Confirmation**  
   - Provides users with the ability to review flight details, select payment options, and confirm their booking.  
   
4. **Login/Logout**  
   - Secure login system for registered users with session handling.  
   
5. **Registration**  
   - A user registration form with validation, allowing users to create an account.  
   
6. **User Profile**  
   - A section where users can view and update their personal information, view past bookings, and manage upcoming itineraries.  
   
7. **Search Features**  
   - Advanced search filters for flights, such as specific airlines, flexible dates, and pricing options.  
   
8. **Itinerary Details**  
   - Displays the user's booked flights with options to print or email details.  
   
9. **About Page**  
   - Information about the airline and how the booking system operates, including customer service details.

---

## 7. Functional Requirements  

- **User Authentication**: The system must allow users to register, log in, and log out securely.  
- **Flight Search**: The system must allow users to search flights using various filters and criteria.  
- **Booking Process**: The system must allow users to book flights, select seats, and confirm their reservation.  
- **Itinerary Management**: Users must be able to view, modify, or cancel their bookings.  
- **Payment Integration**: Integration with popular payment gateways for booking completion.  
- **User Profile**: The system must allow users to update their personal information.  
- **Admin Interface**: Admins must be able to manage flight data, user accounts, and bookings.

---

## 8. Non-Functional Requirements  

- **Performance**: The system should handle up to 100 concurrent users without degradation in response times.  
- **Security**: User data, including payment information, should be encrypted.
- **Usability**: The interface must be intuitive and user-friendly for all types of users.  
- **Scalability**: The system should be able to scale horizontally to accommodate future growth in traffic.  
- **Availability**: The system should maintain a 99.9% uptime.  

---

## 9. Data Requirements  

- **User Data**: Includes user profile information such as name, email, contact information, and booking history.  
- **Flight Data**: Includes flight schedules, seat availability, pricing, and airline details.  
- **Booking Data**: Information on individual bookings, including the user, flight, and payment details.  
- **Payment Data**: Secure storage of payment transaction records in compliance with PCI-DSS standards.

---

## 10. External Interface Requirements  

- **Payment Gateway**: Integration with third-party payment services (e.g., Debit/Credit Card Payments and E-wallets).  
- **Flight Data API**: Integration with external APIs to fetch real-time flight availability and pricing.  
- **Email Service**: Integration with an email service to send booking confirmations and notifications to users.  
- **Web Browser Support**: Compatibility with major browsers (Chrome, Firefox, Safari, Edge).

---

## 11. Glossary  

- **ABS**: Airline Booking System.  
- **Itinerary**: A detailed list of booked flights and schedules for a user.   
- **PCI-DSS**: Payment Card Industry Data Security Standard, ensuring secure handling of payment card information.

---

## 12. Appendices  

- Visual Mockups  
- Entity Relationship Diagram  
