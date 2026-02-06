# Artisian Bakery Website

Welcome to the **Artisian Bakery** project! 🥐🍰 This is a **full-stack bakery website** built with **Flask (Python), HTML, CSS, and JavaScript**, designed to simulate a real online bakery experience.

---

## **Project Features**

- **User Authentication**
  - Signup and login system.
  - Passwords are securely stored.
  - Session-based login for personalized experience.

- **Product Management**
  - Admin can add bakery items with name, price, and image.
  - Specials page displays available bakery items.
  
- **Shopping Cart**
  - Users can add items to cart.
  - Increase or decrease quantity.
  - View cart with total price before placing order.

- **Order Placement**
  - Users can place an order for selected items in the cart.
  - Cart updates dynamically based on user interaction.

- **Responsive Design**
  - Works on desktop and mobile devices.
  - Smooth UI for a pleasant user experience.

---

## **Technology Stack**

- **Backend:** Python, Flask, SQLite
- **Frontend:** HTML, CSS, JavaScript
- **Image Handling:** Pillow
- **Deployment Ready:** AWS (using Gunicorn)
- **Environment Variables:** python-dotenv

---
Create a virtual environment

python -m venv venv


Activate virtual environment

Windows:

venv\Scripts\activate


Linux/Mac:

source venv/bin/activate


Install dependencies

pip install -r requirements.txt


Run the application

python app_aws.py


Access the website

Open your browser and go to:

http://127.0.0.1:5000/

How to Use the Website
1. Homepage

Welcome page with navigation to Login or Signup.

2. Signup

New users must create an account.

Enter username and password.

After signup, you will be redirected to the login page.

3. Login

Existing users enter their credentials.

Successful login redirects to the Specials page.

4. Specials Page

Browse bakery items added by the admin.

Each item shows name, price, and image.

Use “Add to Cart” button to add items to your cart.

5. Cart Page

View items added to the cart.

Increase or decrease item quantity using buttons.

Total price updates automatically.

Click “Place Order” to finalize your order.

6. Admin Features (Optional)

Admin can upload new bakery items using Add Item page.

Images are stored in static/images/.

Database

Uses SQLite (bakery.db).

Tables:

users → stores user credentials.

items → stores bakery items (name, price, image).

cart → stores cart items per user.

