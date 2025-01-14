# Hotel Management System

A comprehensive hotel management system built with **PHP**, **MySQL**, and **HTML/CSS**, designed to simplify and streamline hotel operations such as room booking, customer management, and billing.

---

## Features

- **Room Booking**: Customers can view available rooms and make reservations.
- **Customer Management**: Admins can add, update, and delete customer information.
- **Billing**: Automatic generation of bills based on customer stays.
- **Room Management**: Manage room details such as availability, type, and pricing.
- **Admin Dashboard**: Admin panel for managing bookings, customers, and rooms.
- **Image Integration**: Display room details with images for better user experience.
- **Search and Filter**: Search rooms by type, availability, and price range.

---

## Technologies Used

- **Frontend**:
  - HTML5, CSS3
  - JavaScript (for interactivity)
- **Backend**:
  - PHP (Core PHP for server-side scripting)
- **Database**:
  - MySQL (for data storage and management)
- **Image Storage**:
  - Uploaded images stored in the `images` directory.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hotel-management.git
   cd hotel-management
   ```

2. Set up the database:
   - Create a new MySQL database (e.g., `hotel_management`).
   - Import the provided `database.sql` file into your MySQL database.
     ```bash
     mysql -u your-username -p hotel_management < database.sql
     ```

3. Configure database connection:
   - Open the `config.php` file and update the database credentials:
     ```php
     $servername = "localhost";
     $username = "your-username";
     $password = "your-password";
     $dbname = "hotel_management";
     ```

4. Start the development server:
   ```bash
   php -S localhost:8000
   ```

5. Open your browser and navigate to `http://localhost:8000`.

---

## Project Structure

```
├── images/                 # Contains images for rooms and other assets
├── css/                    # Stylesheets
├── js/                     # JavaScript files
├── includes/               # Common PHP files (e.g., header, footer)
├── config.php              # Database configuration file
├── database.sql            # Database schema and sample data
├── index.php               # Homepage
├── admin/                  # Admin panel files
│   ├── dashboard.php       # Admin dashboard
│   ├── manage_rooms.php    # Room management
│   ├── manage_customers.php # Customer management
├── README.md               # Project README
```


---

## Contributions

Contributions are welcome! Please fork this repository and submit a pull request with your enhancements or bug fixes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---



