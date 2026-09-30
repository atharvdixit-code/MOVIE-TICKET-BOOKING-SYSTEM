# 🎬 Movie Ticket Booking System - VITYARTHI

A CLI-based Movie Ticket Booking System developed in Python. This system allows users to browse movie listings, view seat availability, calculate fares, book or cancel tickets with discount/tax computations, and save booking details persistently.

---

## 👤 Project Information

- **Project Name:** CSE Project - VITYARTHI (Movie Ticket Booking System)
- **Developer:** Atharv Dixit
- **Registration No.:** 26BCE11230
- **Professor:** Dr S.Poonkuntran
- **Slot:** B11+B12+B13+C14+E11+E12

---

## ✨ Features

- 🎟️ **Display Movie Listings:** Browse available movies with showtimes and ticket pricing (Silver/Gold tiering).
- 💺 **Interactive Seat View:** Real-time visual representation of screen and row seat availability (`[A1]` for Available, `[ X ]` for Booked).
- 🍿 **Ticket Booking:** Secure multi-seat selection with automatic availability checks.
- 🏷️ **Discounts & Coupon Codes:** 
  - Automatic **10% Bulk Discount** for booking 4 or more seats.
  - Coupon code support (e.g., `CINEMA10` for a 10% discount).
- 🧮 **Automated Billing & Tax Calculation:** Computes seat subtotal, applied discounts, and 5% GST on the final price.
- 📑 **Receipt Generation:** Generates detailed text receipts for confirmed bookings.
- 💾 **Data Persistence:** Automatically saves and loads booking records from a local file (`bookings.txt`).
- ❌ **Ticket Cancellation:** Allows canceling confirmed bookings via Booking ID or Phone Number, instantly releasing seats back to the system.

---

## 🛠️ Requirements

- **Python:** Python 3.x (No external libraries required)

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
