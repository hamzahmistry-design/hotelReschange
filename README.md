🏨 ACCOMO — Modern Hotel Booking System (Java Edition)
Hey, r/learnprogramming, r/java, r/StudentsWhoCode, and hotel tech enthusiasts — check out ACCOMO! We built a full-stack Java hotel reservation platform with a snazzy UI, real-time features, and secure backend magic. Whether you just want a simple getaway or manage a five-star palace, ACCOMO is here to show how elegant code can make traveling (or just room management) truly accommodating.

🚀 TL;DR
What is it?: Java-powered hotel management & booking app with a slick, user-friendly interface.

Who’s it for?: Anyone — solo backpackers, groups, hotel managers, and devs looking for an awesome project reference.

Coolest features?: Live room availability, secure handling (using multithreaded Java and MySQL), payments, admin dashboard, and filtering galore.

Source code coming soon — but feast your eyes on what it does below!

🎯 Project Highlights:
Search hotels by price, category, and location

Detailed hotel pages — all the info, images, and amenities you need

Sign up/Login — yes, you get an account and can view your bookings

Booking rooms in real time — no overbooking disasters here

Payment gateway support (credit/debit/UPI/QR scan)

Admin powers: Manage hotels, rooms, and pricing (with dynamic updates)

Mobile-friendly design: Runs great on desktop, tablet, or phone

Secure guest data & booking history

Scalable: Built for a boutique inn and a sprawling chain

🖼️ UI Glimpse 

 main landing page — big search bar, hotel listings, cool filters.
<img width="940" height="440" alt="image" src="https://github.com/user-attachments/assets/6ca0d2ad-f5ef-4eb7-b715-ed4157672410" />

Sign-Up / Login Page

<img width="940" height="765" alt="image" src="https://github.com/user-attachments/assets/08b70745-fb91-4c8c-9270-3102c1cedd7b" />

<img width="940" height="405" alt="image" src="https://github.com/user-attachments/assets/47d3de1a-8dd8-409c-bdb4-68468ca08039" />


Hotel Details Page
<img width="940" height="921" alt="image" src="https://github.com/user-attachments/assets/9bdd8e9c-8266-4635-9841-6f0ff4a08cb3" />
<img width="940" height="735" alt="image" src="https://github.com/user-attachments/assets/9633d759-fe61-403d-ab64-f7c6b02fbf50" />



Reservation / Payment Flow
<img width="855" height="730" alt="image" src="https://github.com/user-attachments/assets/850d2ca9-91aa-47e3-a683-78fd6c0202fa" />

Booking forms, calendar pickers, payment popups, QR scanner screens — don’t forget your awesome confirmations and cancellation screens!
<img width="940" height="984" alt="image" src="https://github.com/user-attachments/assets/f571c5bb-a381-4f41-85a8-e19c040853ed" />
<img width="940" height="612" alt="image" src="https://github.com/user-attachments/assets/aa4317aa-2ab3-4e52-b417-0351dd992702" />


🛠️ Core Tech Stack:
Backend: Java (Servlets, Beans, DAO pattern), Apache Tomcat

Frontend: HTML, CSS, JavaScript — styled for comfort, coded for speed

Database: MySQL (ACID-compliant, relational, robust)

Security: OAuth and JWT tokens, validation, encryption

Payment Integration: Credit/Debit card & UPI support — QR code features rock!

Multithreading: No lag with many guests or bookings

IDE of choice: IntelliJ IDEA or Eclipse — take your pick!

🧩 How Does It Work?
Homepage — search, filter, and pick your favorite stay.

Sign Up/Login — simple forms with instant validation and security.

Hotel Details — check reviews, amenities, images, and ratings.

Book a Room — enter dates, guests, room type, and special requests.

Payment — select a method (Card/UPI/QR scan), confirm, and get your booking!

Admin Module — for hotel staff: room updates, pricing tweaks, and live stats.

All wrapped up in modern architecture — RESTful APIs, fast database queries, and robust error handling.
## 🔌 Backend API & Admin Portal

ACCOMO connects its React frontend to a Java Servlet backend through REST-style API endpoints, with MySQL used for persistent application data.

### Key API Endpoints

| Endpoint | Purpose |
|---|---|
| `/api/hotels` | Retrieve hotel listing data |
| `/api/auth` | Customer authentication and session management |
| `/api/reservations` | Retrieve the authenticated customer's reservation history |
| `/api/admin/auth` | Admin login, logout, and authentication state |
| `/api/admin/metrics` | Retrieve dashboard statistics |
| `/api/admin/reservations` | View and manage reservations |
| `/api/admin/customers` | Retrieve customer directory information |
| `/api/admin/payments` | Review payment records and reports |

### Admin Portal

The admin interface provides a centralized dashboard with hotel and room metrics, successful payment totals, reservation management, customer records, and payment reporting.

### Session & Data Protection

Customer reservation history is restricted to authenticated customers, while administrative endpoints require an authorized admin session. The backend validates access before returning protected data.

### Application URL

When deployed on Apache Tomcat with the `/HotelReservation` context path, the application is available at:

`http://localhost:8081/HotelReservation/`

The API endpoints above are relative to the application context path.

✨ Why Build ACCOMO?
Tired of clunky hotel forms and sketchy booking engines? So are we!

“ACCOMO” means accommodation made simple — for staff and guests alike.

Java’s power meets real-world hotel needs: speed, reliability, security.

✅ Future Upgrades — Stay Tuned
AI-powered recommendations (next-level, personalized results)

Multilingual support for a true global audience

Dynamic pricing models (think: hotel surge hours!)

Better mobile experience — maybe a native Android/iOS app? 🤔

 Want to Build This Yourself?
Clone the repo 

Install Java, MySQL, and your favorite IDE

Import the source

Run Apache Tomcat server, connect DB, and go!


