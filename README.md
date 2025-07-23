# ✅ To-Do List Automation Testing (Java + Selenium + TestNG)

This project contains UI automation test scripts for the [Simple To-Do List Web Application](https://eviltester.github.io/simpletodolist/todolists.html) using *Java, **Selenium WebDriver, and **TestNG* following the *Page Object Model (POM)* design pattern.

---

## 📌 Tools & Technologies Used

* *Java 8+*
* *Selenium WebDriver*
* *TestNG*
* *ChromeDriver*
* *IntelliJ IDEA* (or any IDE)
* *Maven* for dependency and build management

---

## ▶ How to Run the Tests

1. *Clone the repository*

   bash
   git clone https://github.com/your-username/todo-list-automation.git
   cd todo-list-automation
   

2. *Open the project in IntelliJ IDEA (or preferred IDE)*

3. *Make sure Java SDK and Maven are installed*

4. *Install dependencies*
   Maven will automatically download dependencies defined in pom.xml:

   bash
   mvn clean install
   

5. *Run the tests*
   Using IntelliJ or via command line:

   bash
   mvn test
   

---

## ✅ Automated Test Scenario

The test performs the following actions:

* Navigate to the [To-Do List Web App](https://eviltester.github.io/simpletodolist/todolists.html)
* Create a new to-do list
* Add multiple to-do items from an array
* Mark an item as completed using the checkbox
* Delete a selected item
* Validate actions using assertions

---

## 📎 Assumptions

* The application is publicly accessible with no authentication required
* Chrome browser is used for all executions
* The structure of the DOM is stable and does not change
* Tests focus on one list at a time
* Basic validations are done through visible text or element presence

---

## 📁 Project Structure


📁 todo-list-automation/

├── src
│   └── main
│       └── java
│           ├── pages
│           │   └── TodoPage.java       # Page Object for To-Do List
│           └── tests
│               └── TodoListTest.java   # Test Class using TestNG
├── pom.xml                             # Maven configuration
├── README.md                           # Project documentation                      

---

## 🔗 Website Under Test

*URL:* [https://eviltester.github.io/simpletodolist/todolists.html](https://eviltester.github.io/simpletodolist/todolists.html)

---
👨‍💻 Author
Ahmed Eldamshity
QA Engineer – Manual & Automation (Java + Selenium)


