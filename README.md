# 🎬 Online Movie Ticket Booking System

A web-based Movie Ticket Booking Management System developed by **Md Sulaiman Qamar**. It is built using **Python (Flask)** and **MySQL**. The application provides separate dashboards for a **Manager** and **Cashier** to manage movies, shows, ticket bookings, and pricing efficiently.

## 🚀 Features

### Manager Dashboard
- 🎥 **Movie Management:** Add and manage details of movies including language and duration.
- 📅 **Show Scheduling:** Schedule movie shows with specific timings and halls.
- 💲 **Price Listing:** Manage and update the ticket pricing for Gold and Standard classes based on the day.
- 📊 **View Bookings:** Monitor booked tickets and allocated seats for each show.

### Cashier Dashboard
- 🎟️ **Ticket Booking:** Book tickets for custom date, show, and seat selection.
- 💺 **Seat Layout:** View interactive seating arrangements (Gold/Standard) to pick available seats.
- 🖩 **Price Calculation:** Automatically retrieve and calculate ticket prices during checkout.

## 💻 Tech Stack

- **Backend:** Python 3.x, Flask (Web Framework)
- **Database:** MySQL (Database), `mysql-connector-python` (Driver)
- **Frontend:** HTML5, CSS3, JavaScript (Jinja2 Templates)

## ⚙️ Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/DevcodeSulaiman/Movie-Ticket-Booking-System.git
cd Movie-Ticket-Booking-System
```

2. **Install Python dependencies:**
Make sure you have Python 3.x installed. Then, run:
```bash
pip install -r requirements.txt
```

3. **Database setup:**
- Create a MySQL database named `dbtheatre`.
- Import the `dbtheatre.sql` (or equivalent database dump file) into your MySQL server to set up tables and initial data.
- Open `app.py` (around line 386) and update the MySQL connection `password` with your local database password (currently marked as `YOUR_PASSWORD`).

4. **Run the application:**
```bash
python app.py
```

5. **Access the application:**
Open your browser and visit:
```
http://localhost:5000
```

## 🔐 Default Login Credentials

### Manager
- **Username:** `manager`
- **Password:** `Password@123`

### Cashier
- **Username:** `cashier`
- **Password:** `cashier123`

## 📁 Project Structure

```text
Movie-Ticket-Booking-System/
├── app.py                 # Main Flask application file containing all routes
├── database file/         # MySQL database dump
├── static/                # CSS, JS, and Images for the frontend UI
├── templates/             # HTML templates (Jinja2) for UI rendering
├── requirements.txt       # Python dependencies (Flask, mysql-connector-python)
└── README.md              # Project documentation
```

## 🔮 Future Improvements

- Database-based dynamic user authentication
- Password hashing and encryption
- Email notifications for successful bookings
- Integration with an online payment gateway
- Fully responsive UI layout for mobile devices

## 📄 Notes

This project was developed by Md Sulaiman Qamar and is intended for learning and educational purposes.