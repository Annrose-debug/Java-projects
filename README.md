# Bread Recipe Manager 🍞

A Java application for managing bread recipes and generating shopping lists based on ingredient quantities.

## 📌 Project Overview
- **Purpose**: Manage multiple bread recipes and generate shopping lists based on desired quantities
- **Course**: Assignment 3 for [Course Name] at Algonquin College
- **Key Features**:
  - Recipe storage with ingredient tracking
  - Shopping list generation
  - File I/O operations for persistence

## 🛠️ Technologies Used
- Java 11+
- File I/O (`java.io`)
- Collections Framework (`java.util`)

## 📂 File Structure
```
src/
├── assn3/
│   ├── Recipe.java            # Recipe entity class
│   ├── RecipeManager.java     # Manages recipes and shopping lists
│   └── assignment.java        # Main driver class
data/
├── recipelist1.txt            # Input recipe data
└── shoppinglist.txt           # Generated shopping lists
```

## 🧾 Sample Recipe File Format (`recipelist1.txt`)
```
Recipe White Bread
eggs 2
yeast 10
flour 500
sugar 20
butter 30

Recipe Whole Wheat Bread
...
```

## 🚀 How to Run
1. Ensure Java JDK 11+ is installed
2. Compile all Java files:
   ```bash
   javac assn3/*.java
   ```
3. Run the program:
   ```bash
   java assn3.assignment
   ```

## 🖥️ Program Menu
```
Welcome to Algonquin College's recipe manager.
Please select one of the following options:
1. Show available recipes.
2. Create Shopping List.
3. Print Shopping List.
4. Quit Program.
0. to reprint this menu.
```

## 📝 Key Functionality
- **Recipe Management**:
  - Load recipes from text file
  - Track ingredients (eggs, yeast, flour, sugar, butter)
- **Shopping List**:
  - Calculate total ingredients needed
  - Save to `shoppinglist.txt`

## 👩‍💻 Developer
- **Name**: Annrose Akande
  
## ⚠️ Notes
1. Place `recipelist1.txt` in the project root directory
2. Generated `shoppinglist.txt` will appear in the same directory
3. For best results, use absolute file paths in `RecipeManager.java`

## 📄 License
This project is for educational purposes only.
