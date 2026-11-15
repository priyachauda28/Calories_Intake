# 🥗 Calorie Intake Tracker

A fully client-side, single-file calorie tracking web app built with plain HTML, CSS, and JavaScript. No installation, no backend, no build steps — just open the file in a browser.

**Live Demo:** [https://priyachauda28.github.io/Calories_Intake/calorie_tracker.html](https://priyachauda28.github.io/Calories_Intake/calorie_tracker.html)

---

## ✨ Features

### 🍎 Food Entry
- Search from a built-in database of **88+ common foods** (fruits, vegetables, grains, protein, dairy, snacks, beverages)
- Quantity field with unit selector: **Piece / Bowl / Cup / Gram / ml**
- Manual calorie entry for foods not in the database
- Autocomplete suggestions with calories per 100g shown

### 👤 Personalized Profile
- Set your **Name, Gender, Age, Weight, Height, and Activity Level**
- Daily calorie goal calculated using the **Mifflin-St Jeor formula** with activity multiplier
- Profile saved to `localStorage` — persists across sessions

### 📊 Dashboard
- **Circular progress ring** showing calories consumed vs. daily goal (color shifts orange → red as you approach/exceed goal)
- **4 KPI tiles:** Calories Consumed, Calories Remaining, Daily Goal, Items Logged
- **Macro breakdown bars** for Carbs, Protein, and Fat (normalized to recommended daily targets)
- **Doughnut chart** — calorie distribution by food category
- **Bar chart** — calories per individual food entry

### 📚 Daily Nutrition Guide Panel
- Recommended daily calorie ranges by gender and age group
- Macronutrient split guidelines (Carbs 45–65%, Protein 10–35%, Fat 20–35%)
- Micronutrient highlights (fiber, water, sugar, sodium)
- **Dynamic tip** that updates based on your actual intake

### 📋 Food Log Table
- Scrollable table: Food | Category | Quantity | Unit | Calories | Time | Remove
- **Clear Today** button to reset the day's entries
- Totals row at the bottom

### 🎨 Design
- Green health-themed color scheme with gradient accents
- **Dark / Light mode toggle**
- Fully responsive — works on mobile and desktop
- Category color badges for quick visual scanning

---

## 🚀 Getting Started

### Option 1 — Open locally
```
Download calorie_tracker.html → double-click to open in any browser
```

### Option 2 — GitHub Pages (live)
```
https://priyachauda28.github.io/Calories_Intake/calorie_tracker.html
```

No npm, no Node.js, no server required.

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 (custom properties) | Theming, layout, animations |
| Vanilla JavaScript (ES6+) | Logic, state, persistence |
| [Chart.js 4.4](https://www.chartjs.org/) | Doughnut & bar charts (CDN) |
| localStorage | Profile + daily log persistence |

---

## 🧮 Calorie Goal Formula

**Mifflin-St Jeor BMR:**
```
Male:   BMR = (10 × weight kg) + (6.25 × height cm) − (5 × age) + 5
Female: BMR = (10 × weight kg) + (6.25 × height cm) − (5 × age) − 161
```

**Daily Goal = BMR × Activity Multiplier**

| Activity Level | Multiplier |
|---|---|
| Sedentary (desk job, no exercise) | 1.2 |
| Lightly Active (1–3×/week) | 1.375 |
| Moderately Active (3–5×/week) | 1.55 |
| Very Active (6–7×/week) | 1.725 |

---

## 🗂 Food Database Categories

| Category | Examples |
|---|---|
| 🍎 Fruits | Apple, Banana, Mango, Avocado, Blueberry |
| 🥦 Vegetables | Broccoli, Spinach, Sweet Potato, Mushroom |
| 🍚 Grains | Rice, Chapati, Oats, Pasta, Quinoa |
| 🍗 Protein | Chicken Breast, Eggs, Dal, Salmon, Tofu |
| 🥛 Dairy | Milk, Yogurt, Cheese, Butter, Ice Cream |
| 🍕 Snacks | Pizza, Burger, Chocolate, Chips, Donut |
| ☕ Beverages | Coffee, Tea, Cola, Juice, Smoothie |

---

## 📁 Project Structure

```
Calories_Intake/
└── calorie_tracker.html   # Complete app — all HTML, CSS, JS in one file
└── README.md              # Project documentation
```

---

## 📸 Screenshots

> Dashboard with progress ring, KPI tiles, and macro bars  
> Food log table with category badges  
> Dark mode support  
> Nutrition guide sidebar with personalized tips  

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋 Author

**Priya Chauda** — [@priyachauda28](https://github.com/priyachauda28)
