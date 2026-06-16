# KabadiMarket.com — Chapra ka #1 Scrap Platform

> PHP/MySQL scrap collection platform with booking system, 
> rate calculator, admin panel and WhatsApp integration

![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?style=flat&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql)
![Live](https://img.shields.io/badge/Live-kabadimarket.com-green?style=flat)

## 🌐 Live Site
**[www.kabadimarket.com](https://www.kabadimarket.com)**

## 📋 About
Chapra (Bihar) ke liye scrap collection platform — ghar baithe 
kabadi sell karo, free doorstep pickup, instant cash/UPI payment.

## ✨ Features
- 📅 Online pickup booking with WhatsApp confirmation
- 💰 Live scrap rate calculator (16+ materials)
- 🛠️ Admin panel — bookings + rates management
- 📱 Mobile-first responsive design
- 💬 WhatsApp direct integration
- 🌍 Environmental impact tracker
- ⭐ Customer reviews section
- 📍 Service area coverage map

## 🏷️ Scrap Categories
| Category | Materials | Rate Range |
|----------|-----------|------------|
| Paper | Newspaper, Cardboard, Books | ₹6–₹15/kg |
| Plastic | Hard, Soft, Mix | ₹10–₹12/kg |
| Metal | Iron, Copper, Aluminium, Steel | ₹25–₹320/kg |
| E-Waste | Mobile, Laptop, Charger | ₹20–₹500/pcs |

## 🛠️ Tech Stack
- **Backend:** PHP 8.2
- **Database:** MySQL 8.0
- **Frontend:** HTML5, CSS3, Vanilla JS
- **Integration:** WhatsApp Business API
- **Hosting:** Shared Hosting / VPS

## 📁 Project Structure

kabadi-market/

├── admin/              # Admin panel

│   ├── index.php       # Dashboard — bookings + stats

│   ├── bookings.php    # Manage all bookings

│   └── rates.php       # Update scrap rates

├── includes/

│   ├── db.php          # Database connection

│   └── functions.php   # Helper functions, rates, booking

├── database/

│   └── kabadi_market.sql  # Full schema + seed data

├── booking.php         # Pickup booking form + AJAX handler

├── rates.php           # Live rate list page

├── services.php        # Services page

├── about.php           # About page

└── contact.php         # Contact form


## ⚙️ Local Setup

```bash
# 1. Clone karo
git clone https://github.com/nirajtech15/kabadi-market.git
cd kabadi-market

# 2. Database import karo
mysql -u root -p < database/kabadi_market.sql

# 3. Environment setup
cp .env.example .env
# .env mein DB credentials daalo

# 4. XAMPP/Laragon mein run karo
# htdocs/kabadi-market/ mein rakho
# http://localhost/kabadi-market/
```

## 📸 Screenshots
![Home Page](screenshots/home.png)
![Booking Form](screenshots/booking.png)
![Rate Calculator](screenshots/calculator.png)
![Admin Panel](screenshots/admin.png)



## 👨‍💻 Developer
**Er. Niraj Singh** — Senior Full-Stack Developer  
[GitHub](https://github.com/nirajtech15) · 
[BiharBusiness.com](https://biharbusiness.com)
