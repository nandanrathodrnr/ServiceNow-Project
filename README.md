# ServiceNow-Project
🚇 Metro Ticket Booking System (ServiceNow)
📌 Project Overview

The Metro Ticket Booking System is built using ServiceNow to provide a digital solution for booking metro tickets and recharging metro cards. Users can easily select journey details, calculate fare automatically, and complete payments using QR code or other methods.

🎯 Features
🎫 Book metro tickets (Single / Return)
💳 Recharge metro card
📍 Select source and destination stations
👥 Enter number of passengers
💰 Automatic fare calculation
📱 QR Code for Scan & Pay
💵 Multiple payment modes (Cash, Card, UPI)
📊 Order confirmation and request tracking
🛠️ Technologies Used
ServiceNow Platform
Catalog Item & Service Catalog
Client Scripts (onChange, onLoad)
UI Policies
Flow Designer
Service Portal
🧩 Modules Implemented
Catalog Item: Book a Metro Ticket
As shown in page 1, the catalog item is created under Service Catalog.
Variables Configuration
Multiple fields like:
Starting From
Going To
Number of Passengers
Type of Journey
Payment Mode
(Refer page 3)
UI Policies
Show/Hide fields dynamically based on user selection
(Refer page 4)
Client Scripts
Used for fare calculation and validation
(Refer page 5)
Service Portal Interface
User-friendly booking interface
(Refer page 8–13)
QR Code Payment
Scan and pay option implemented
(Refer page 16)
Order Confirmation
Displays booking details after submission
(Refer page 18–21)
⚙️ Workflow
User searches "Book Metro Ticket"
Selects ticket type (Recharge / Book Ticket)
Enters journey details
System calculates fare automatically
User selects payment mode
QR code is generated for payment
Order is placed and confirmation is generated
📷 Screenshots

Project screenshots are included in the documentation showing:

Catalog setup
Variable configuration
UI behavior
Payment integration
Final output
🚀 Advantages
Reduces manual ticket booking
Fast and secure payment system
User-friendly interface
Automated fare calculation
Digital ticket management
🔮 Future Enhancements
Integration with real metro APIs
Live train timing updates
Mobile app integration
Ticket history & analytics dashboard
👨‍💻 Author

Nandan Rathod
Final Year Engineering Student (CSE)
