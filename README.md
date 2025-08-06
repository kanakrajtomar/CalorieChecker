# CalorieChecker

A simple Java-based console application that calculates and displays the user's daily calorie intake based on input data like age, gender, weight, height, and activity level.

---

## 🚀 Features

* Takes user inputs like age, weight, height, gender, and activity level
* Calculates Basal Metabolic Rate (BMR)
* Adjusts for activity level to determine daily calorie needs
* Displays results in a user-friendly format
* Clean code structure using OOP principles (Java)

---

## 🛠️ Tech Stack

* **Language:** Java
* **Concepts Used:** OOP (Classes, Objects), Input Handling, Encapsulation

---

## 📁 File Structure

```
CalorieChecker/
├── CalorieCalculator.java        # Logic for calculating calorie needs
├── MainApp.java                  # Entry point of the application
├── ResultDisplay.java            # Handles formatted result output
├── UserData.java                 # Data model to hold user info
├── UserInputHandler.java         # Handles input from the user
```

---

## 🔄 How It Works

1. User runs the application
2. `UserInputHandler` collects all required inputs
3. `CalorieCalculator` processes the data
4. `ResultDisplay` outputs the final calorie estimate

---

## 🎯 Purpose

This project demonstrates clean object-oriented design in Java and serves as a learning tool for:

* Structuring medium-size Java programs
* Practicing user input, data flow, and modular design

---

## 📌 Usage

Compile and run the `MainApp.java` file:

```bash
javac MainApp.java
java MainApp
```

Follow the console prompts to input your data and receive a personalized calorie report.

---

## 🧠 Future Improvements

* Add file storage or database for user history
* GUI version with JavaFX or Swing
* Integration with fitness APIs for more accurate calculations

---

## 👨‍💻 Author

**Kanak Raj Tomar**
GitHub: [kanakrajtomar](https://github.com/kanakrajtomar)

---

## 📜 License

This project is open-source and available under the MIT License.
