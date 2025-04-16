
# Restaurant Management System

A full-featured Restaurant Management System designed to streamline and digitize restaurant operations. It includes modules for Dine-In, Takeout, and Delivery services with a focus on usability, efficient order handling, and seamless payment integration.

## Features

### Order Management
- Manage orders for Dine-In, Takeout, and Delivery.
- Real-time updates on order status.
- Auto-generated order receipts and timestamps.

### Dine-In Module
- Table reservation and assignment.
- QR-based digital menu with contactless ordering.
- Real-time table status (Available, Reserved, Occupied).

### Takeout Module
- Customers can schedule pickup times.
- Notifications for order preparation and readiness.
- OTP-based pickup confirmation.

### Delivery Module
- Delivery address input with map integration.
- Delivery partner assignment with real-time tracking.

### Admin Dashboard
- Sales tracking by order type.
- Inventory and ingredient monitoring.
- Staff management and analytics.

### Payment Integration

- Secure, encrypted API for checkout and transactions.

### User Management
- Customer registration, login, and order history.
- Admin and Staff roles with access control.

## Tech Stack

- Frontend: HTML, CSS,Bootstrap
- Backend: PHP 
- Database: MySQL / MongoDB
- Hosting/Tools: XAMPP 
  
## System Requirements

- XAMPP / WAMP server (for PHP & MySQL)
- Modern browser


## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/restaurant-management-system.git
   ```
2. Set up the database using the provided `.sql` file.
3. Configure `config.php` or `.env` file with your DB/API keys.
4. Launch the project using XAMPP/WAMP or run `npm start`.
5. Open `http://localhost/restaurant-management-system` in your browser.

## Future Enhancements

- Loyalty points and reward system
- Customer feedback and review module
- AI-based menu suggestions
- Multilingual support
