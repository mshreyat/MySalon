# MySalon – Beauty Services Marketplace

A desktop application built with **Python**, **MySQL**, and **Tkinter** that connects customers with beauty service providers. It offers service listings, price comparisons, and location-based booking using the **Google Maps API**. MySalon empowers small businesses by improving digital visibility and streamlining appointment scheduling.

---

## 🚀 Features
- ✅ Browse beauty service providers with detailed listings  
- ✅ Compare service prices and availability  
- ✅ Book appointments in real-time with location-aware suggestions  
- ✅ Manage customer profiles and service history  
- ✅ Interactive and user-friendly interface with Tkinter

---

## 🛠 Tech Stack
- **Backend:** Python, MySQL  
- **Frontend:** Tkinter  
- **APIs:** Google Maps API for location services  
- **Database:** MySQL for storing user profiles, appointments, and service data

---

## 📂 Project Structure

# 1. Prerequisites
- Python 3.8+
- MySQL Server
- Git (for collaboration)

# 2. Database Setup
### 1. Create database (one-time)
mysql -u root -p -e "CREATE DATABASE salon_management;"

### 2. Import schema
mysql -u root -p salon_management < schema.sql

# 3. Configure Environment
### 1. Copy the example env file
cp .env.example .env

### 2. Edit with your credentials
nano .env  # or use any text editor

# 4. Install Dependencies
pip install -r requirements.txt

# 5. Run the Application
python salon_app.py

