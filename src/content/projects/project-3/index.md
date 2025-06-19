---
title: 'Inventroy Management'
description: 'A full-stack web application for managing products and categories, designed to streamline inventory tracking for small businesses and retailers'
date: 'Apr 08 2025'
repoURL: 'https://github.com/gazzaar/inventory-management'
---

A full-stack web application for managing products and categories, designed to streamline inventory tracking for small businesses and retailers.

## Project Highlights

- **Modern Full-Stack Architecture:**  
  Built with Node.js, Express, and EJS for dynamic server-side rendering.

- **Modular Codebase:**  
  Clean separation of concerns with controllers, models, and routes for maintainability and scalability.

- **Responsive UI:**  
  Custom CSS for a user-friendly, mobile-responsive interface.

- **Database Integration:**  
  Efficient PostgreSQL connection pooling and query management.

- **RESTful API Design:**  
  Well-structured endpoints for products and categories.

- **Easy Extensibility:**  
  Designed for adding new features such as authentication, reporting, or analytics.

---

## Features

- **Product Management:**  
  Add, view, and manage products with details like name, category, and quantity.

- **Category Management:**  
  Organize products into categories for easier navigation and reporting.

- **Dashboard Views:**  
  Clean, intuitive pages for listing products and categories.

- **Reusable Components:**  
  EJS partials for headers and shared UI elements.

---

## 📂 Project Structure

```
src/
  controllers/   # Business logic for products & categories
  models/        # Database connection & queries
  routes/        # Express route definitions
  views/         # EJS templates for UI
  public/css/    # Custom stylesheets
  server.js      # App entry point
```

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, CSS
- **Database:** PostgreSQL

---

<!---->
<!-- ## 📸 Screenshots -->
<!---->
<!-- > _Add screenshots or GIFs here to showcase the UI and features!_ -->
<!---->
<!-- --- -->

## 🏗️ How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/gazzaar/inventory-management.git
   cd inventory-management
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Configure your database:**

   - Update connection settings in `src/models/pool.js`.

4. **Run the app:**
   ```bash
   npm start
   ```
   - Visit `http://localhost:3000` in your browser.

---

## 📄 License

This project is licensed under the MIT License.
