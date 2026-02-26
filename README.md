# 🌿 Smart Pesticide Guide (Enhanced Prototype v2)

An AI-powered prototype web application that helps farmers detect plant pests and calculate the correct pesticide dosage based on crop type and land area.

---

## 📌 Project Overview

Smart Pesticide Guide is a frontend-based prototype that:

- 📸 Accepts plant/pest image upload
- 🔍 Simulates AI pest detection
- 🧴 Suggests suitable pesticide
- 🧪 Displays active ingredients
- ⚠️ Shows safety precautions
- 📏 Calculates pesticide dosage (Acre / Hectare / m²)

This project is built using **HTML, CSS, and JavaScript** only.

---

## 🚀 Features

### 1️⃣ Image Upload (Simulated)
- User uploads a plant/pest image.
- Detection is simulated using:
  - Filename keyword matching
  - Random fallback selection

### 2️⃣ Pest Detection (Prototype Logic)
- Matches keywords like:
  - aphid
  - fungus
  - worm
  - beetle
- Returns:
  - Pest name
  - Confidence %
  - Recommended pesticide

### 3️⃣ Crop Selection
Supported crops:
- 🌾 Wheat
- 🍚 Rice / Paddy
- 🧶 Cotton
- 🌽 Maize
- 🥬 Vegetables
- 🍎 Fruits

### 4️⃣ Pesticide Recommendation
Displays:
- Product name
- Active ingredients
- Dosage reference
- Crop compatibility
- Safety instructions

### 5️⃣ Dosage Calculator
User enters:
- Area value
- Unit (Acre / Hectare / m²)

System calculates:
- Total pesticide required
- Converts ml to Liters automatically if > 1000 ml

---

## 🧪 Sample Pesticides in Database

| ID | Name | Active Ingredient |
|----|------|------------------|
| pest-001 | ImidaSafe 200 | Imidacloprid |
| pest-002 | FungiGuard | Copper Oxychloride |
| pest-003 | BioNeem 50 | Azadirachtin |
| pest-004 | CyperMaster 10EC | Cypermethrin |

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Responsive UI)
- JavaScript (Vanilla JS)
- Simulated AI Logic

---

## 📂 Project Structure
