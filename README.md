<img width="1456" height="720" alt="Gemini_Generated_Image_j5x77uj5x77uj5x7" src="https://github.com/user-attachments/assets/55ba6c35-9b53-43df-9dab-d857a50b2830" />

# ☕ CoffeeBuddy

CoffeeBuddy is a **basic PHP & MySQL coffee ordering platform** (about **80% complete**) inspired by Swiggy.  
It allows users to browse coffee shops, view products, customize orders with add-ons, and place an order.  

---

## 🚀 Current Features

### 👥 User Side
- Browse available coffee shops  
- View and select coffee products from each shop  
- Customize orders with add-ons (milk type, toppings, sugar, etc.) or skip customization  
- Add products to cart and proceed to checkout  
- Responsive layout for mobile and desktop  

### 🔐 Admin Side (Basic)
- Add/Edit/Delete Shops  
- Add/Edit/Delete Products  
- Manage Categories and Add-ons  
- View Orders  

---

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, Bootstrap 5, FontAwesome  
- **Backend**: PHP (Core PHP)  
- **Database**: MySQL  
- **Server**: XAMPP / Apache (localhost)  

---

## 📂 Project Structure
coffee-buddy/
├── admin/ # Admin panel files
├── user/ # User-facing pages
├── classes/ # Data access class
├── config/ # Configuration & DB connection
├── uploads/ # Uploaded images
├── assets/ # CSS & images
└── README.md

markdown
Copy
Edit

---

## ⚙️ Setup Instructions

1. **Clone or download** the project  
2. **Create a MySQL database** (e.g., `coffee`)  
3. **Import** the provided `coffee.sql`  
4. **Update** `config/autoload.php` with DB credentials  
5. Move the folder to `htdocs` and run via **XAMPP/WAMP**  
6. Access:  
http://localhost/coffee-buddy/user/shop.php

yaml
Copy
Edit

---

## 📌 Notes
- Additional items are stored as comma-separated IDs in the database  
- Session variables track product ID and user email  
- Some features and security measures are still pending (about 20% remaining work)  

---

## 🚧 Remaining Work (20% Pending)
- User authentication & registration  
- Order history & tracking  
- Payment gateway integration  
- Input validation & sanitization  
- Image upload in admin panel  

---

## 📬 Contact
**Project by:** Pauljo George  
**Email:** pauljogeorge45@gmail.com
