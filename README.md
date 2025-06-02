# SpeedyWheels – Car Rental Service

A simple interactive car rental single-page web application that lets users browse a selection of vehicles, filter and search based on their needs, and place a reservation, all with a clean, responsive UI and real-time feedback.

---

## Features

- **Interactive Car Catalogue:**  
  Browse available vehicles with images, detailed info, and live status.
- **Search & Filter:**  
  Instantly search by brand, model, fuel type, or car type; filter by brand/type with dropdowns.
- **Reservation System:**  
  Users can reserve a car by filling out a detailed form, with live validation and total price calculation.
- **Confirmation Flow:**  
  Upon reserving, users see a confirmation screen simulating an email confirmation step.
- **Responsive & User-friendly:**  
  Designed to work well on both desktop and mobile, with visually appealing styles and icons.
- **State Persistence:**  
  Selected car and partially completed form data are stored in the browser (localStorage) for a smoother experience.
- **Demo Data:**  
  Car inventory and existing reservations are pre-loaded as JavaScript objects.

---

## How It Works

1. **Landing Page:**  
   - The homepage displays a grid of available cars.
   - Users can search and filter cars using the search bar and dropdowns.
2. **Viewing Cars:**  
   - Each car card shows key info: image, type, brand, model, year, mileage, fuel, price, and availability.
   - “Rent Now” is enabled only for available cars.
3. **Reservation:**  
   - Clicking “Rent Now” takes the user to a reservation form for that car.
   - Form fields include name, phone, email, driver’s license, rental start date, and rental duration.
   - Real-time validation ensures all info is correctly entered.
   - The total price is calculated and shown instantly.
4. **Order Confirmation:**  
   - Submitting the form displays a reservation confirmation page.
   - A simulated confirmation link is presented.
   - Returning to the homepage, the car is now shown as unavailable.
5. **Navigation:**  
   - The header logo always brings users home.
   - A “Reservation” button provides quick access to the reservation page.

---

## File Structure

- `index.html` – Main HTML file, includes embedded CSS and JS.
- `images/` – Contains images for cars (add your own for demo).
- **No external dependencies** other than FontAwesome and jQuery/jQueryUI via CDN.

---

## Setup & Usage

1. **Download or Clone the Repository**

   ```bash
   git clone <>
   cd speedywheels
