# 🎬 Movie Ticket Booking Management System

A web-based Movie Ticket Booking Management System developed using **Python (Flask)** and **MySQL**. The application provides separate dashboards for **Manager** and **Cashier** to manage movies, shows, ticket bookings, and pricing.

## Features

- 🔐 Manager Login
- 🎟️ Cashier Login
- 🎥 Movie Management
- 📅 Show Scheduling
- 💺 Seat Booking
- 💲 Ticket Price Management
- 🗄️ MySQL Database Integration

## Tech Stack

- Python
- Flask
- MySQL
- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Movie-Ticket-Booking-System.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Create a MySQL database named:

```
dbtheatre
```

4. Import the `dbtheatre.sql` file into MySQL.

5. Open `app.py` and update your MySQL credentials.

6. Run the application

```bash
python app.py
```

7. Open your browser and visit

```
http://localhost:5000
```

## Login Credentials

### Manager

- Username: `manager`
- Password: `Password@123`

### Cashier

- Username: `cashier`
- Password: `cashier123`

## Project Structure

```
Movie-Ticket-Booking-System
│
├── app.py
├── dbtheatre.sql
├── static/
├── templates/
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Database-based authentication
- Password encryption
- Email notifications
- Online payment gateway
- Responsive UI
- Admin dashboard enhancements

## License

This project is intended for learning and educational purposes.