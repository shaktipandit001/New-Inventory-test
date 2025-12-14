# 📦 Inventory Tracker – Professional Multi-Location System

A comprehensive and secure **inventory management system** designed for businesses operating across multiple locations.
Includes monthly inventory tracking, product catalog management, user access control, analytics, and robust security features — all running **entirely in the browser**.

---

## 🌟 Features

### 🔒 Security System

* Multi-layer protection with **custom access codes**
* **Session-based authentication** with expiration
* Built-in **developer tools prevention**
* **Role-based access control** (Admin / Inventory User)

### 📊 Inventory Management

* Monthly inventory counting with **automatic closing dates**
* **Decimal quantity support** (KG, liters, etc.)
* **Multiple locations** (Ostbahnhof, Potsdam, expandable)
* Real-time inventory **value calculation**
* Read-only mode for closed periods

### 🏪 Product Catalog

* **400+ preloaded products** across multiple categories:

  * Verbrauch (Consumables)
  * Trockenware (Dry Goods)
  * TK Allgemein (Frozen Goods)
  * Gemüse (Fresh Produce)
  * Retail
  * Non-Food
  * Frischwaren (Fresh Goods)
* Automatic category grouping
* Product **search & filter**
* Supports units like KG, Stück, Packung, Liter, etc.

### 👥 User Management

* Admin & Inventory User roles
* Location-specific access
* User activity tracking
* Secure password system

### 📈 Analytics & Reporting

* Real-time value overview
* Category-wise distribution
* Monthly archives
* Data export for backups

### 📱 User Interface

* Fully **responsive** layout
* Tab-based navigation
* Interactive charts (Chart.js)
* Clean, intuitive dashboard

---

## 🚀 Quick Start

### Prerequisites

* Any modern web browser (Chrome, Firefox, Safari, Edge)
* No server, no installation required

### Installation

```bash
git clone https://github.com/yourusername/inventory-tracker.git
```

Then simply open:

```
index.html
```

### Initial Access Codes (case-sensitive)

```
NEPAL
SHAKTIINV24
FOODSERVICES
HAFERKATER
INVENTORY2024
```

### Default Login Credentials

| Role           | Username | Password    |
| -------------- | -------- | ----------- |
| Admin          | `admin`  | `add`       |
| add            | `add `   | `add`       |
| Inventory User | `rakesh` | `rakesh123` |
| Inventory User | `khalil` | `khalil123` |

---

## 📖 How to Use

### 1. First-Time Setup

1. Enter an access code
2. Log in as Admin
3. System auto-loads 400+ products

### 2. Inventory Counting

* Select month & location
* Use `+1` and `-1` for quick adjustments
* Enter decimals for KG/Liter
* Click **Apply** for custom adjustments

### 3. Add New Products

1. Go to **All Products**
2. Click **Add New Product**
3. Fill in product ID, name, category, unit, and price

### 4. Manage Users

* Admin Panel → Manage Users
* Add/Edit/Delete users
* Assign access per location

### 5. Monthly Archives

* Browse past months
* Compare inventory trends
* Export data for reporting

---

## 🛠 Technical Details

### Data Storage

* Uses **LocalStorage** for persistence
* Completely client-side
* Supports full data **export/import**

### Security

* Password encryption
* Session validation
* Anti-tampering features
* Right-click & keyboard shortcut blocking

### File Structure

```
inventory-tracker/
├── index.html
├── README.md
└── (no additional files required)
```

---

## 📊 Product Categories

**Main Categories**

1. Verbrauch
2. Trockenware
3. TK Allgemein
4. Gemüse
5. Retail
6. Non Food
7. Frischwaren
8. Sammel CM 0

**Supported Units**

* KG
* Stück
* Packung
* Kiste
* Beutel
* Liter
* Schale

---

## 🔧 Admin Functions

### User Management

* Create/edit/delete users
* Assign roles
* Location-based access
* Login history overview

### Location Management

* Add/remove locations
* Activate/deactivate locations
* Set custom IDs

### Data Management

* Export all data (JSON)
* Reset monthly counts
* View analytics

---

## 📱 Mobile Support

Runs perfectly on:

* Desktop
* Tablet
* Smartphone
* Any modern browser

---

## ⚠️ Important Notes

### Data Persistence

* Stored locally in the browser
* Regular exports recommended
* Data is device/browser specific

### Security Tips

* Change default passwords after installation
* Do not share access codes publicly
* Always log out after use

### Inventory Dates

* Monthly periods close automatically on the **10th**
* Closed months become read-only

---

## 🔄 Updates & Maintenance

### New Products

* Add via UI
* Import via JSON
* Bulk import available on request

### Customization

* Modify CSS for branding
* Add categories or product lists
* Expand locations as needed

---

## 🤝 Support

For issues or feature requests:

1. Check the issue tracker
2. Open a new issue
3. Contact the developer if needed

---

## 📄 License

This software is **proprietary** and intended for internal business use only.

---

## 🙏 Credits

**Developed by Shakti**
Professional Inventory Management Solutions

---


