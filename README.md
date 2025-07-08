# Meals App

A Flutter-based recipe browsing application that helps users discover meals based on different categories, mark favorites, and apply dietary filters like gluten-free, vegan, and lactose-free.

---

## Features

- Browse meals by categories (e.g., Italian, Quick & Easy, Hamburgers)
- View detailed recipe instructions and ingredients
- Filter meals based on dietary restrictions:
  - Gluten-free
  - Vegan
  - Vegetarian
  - Lactose-free
- Mark and unmark meals as favorites
- Light and dark theme toggle
- Responsive and smooth navigation experience

---

## Tech Stack

- **Flutter** & **Dart**
- **State Management**: setState (no external package)
- **Routing**: Navigator 1.0
- **Custom Widgets** and structured screens

---

## Screens

- **Categories Screen**: Grid of meal categories
- **Meals Screen**: Meals listed per category
- **Meal Detail Screen**: Full recipe view
- **Filters Screen**: Toggle switches for dietary preferences
- **Favorites Screen**: View saved meals

---

## Getting Started

### Prerequisites

- Flutter SDK installed
- IDE like VS Code or Android Studio

### Installation

```bash
git clone https://github.com/yourusername/meals-app.git
cd meals-app
flutter pub get
flutter run
