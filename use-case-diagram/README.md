# Airbnb Clone Backend - Features & Functionalities

This document outlines the key features and technical requirements for the Airbnb Clone backend system. The diagram `airbnb-backend-features.png` provides a high-level view of the components and relationships.

## 🎯 Core Features

### 1. User Management
- Register/Login (JWT & OAuth)
- Profile management
- Role-based access (Guest, Host, Admin)

### 2. Property Listings
- Host can create/update/delete properties
- Properties contain amenities, price, availability

### 3. Search & Filter
- Search by location, date, guest count
- Filter by price range and amenities
- Pagination support

### 4. Booking System
- Book available property
- Prevent double bookings
- Cancel bookings with proper status updates

### 5. Payments
- Secure payment (Stripe, PayPal)
- Auto payouts to hosts
- Payment status tracking

### 6. Reviews
- Guests can rate/review properties post-stay
- Reviews linked to bookings
- Hosts can respond

### 7. Notifications
- Email + in-app alerts for bookings, cancellations, and payments

### 8. Admin Dashboard
- Manage platform: users, listings, reviews, and transactions

## 🛠️ Technical Stack
- **Database**: PostgreSQL / MySQL
- **API**: RESTful with optional GraphQL
- **Auth**: JWT, OAuth (Google, Facebook)
- **File Storage**: AWS S3 / Cloudinary
- **Email**: SendGrid / Mailgun
- **Caching**: Redis (optional)
- **Testing**: Pytest
- **Logging & Error Handling**: Centralized

## 📊 Diagram
See `airbnb-backend-features.png` for system architecture and module relationships.
