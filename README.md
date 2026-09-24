# CubeCart E-Commerce Automation Framework

A clean, structured Selenium + TestNG + Cucumber automation framework built for Software Testing freshers & SDET job interviews.

---

## 1. Project Overview & Features
* **Application Under Test (AUT):** CubeCart Demo Store (`https://javabykiran.in/other/CC`)
* **Design Pattern:** Page Object Model (POM) for high reusability and easy maintenance.
* **Execution Support:** Both plain TestNG test suites and Cucumber BDD (Gherkin feature files) are integrated.
* **Modules Automated:** 
  1. User Registration (33 tests)
  2. User Login (2 tests)
  3. Admin Login (23 tests)
  4. Inventory Navigation (20 tests)
  5. Add Product (35 tests)

---

## 2. Technology Stack
* **Language:** Java 17
* **Automation Tool:** Selenium WebDriver 4
* **Test Framework:** TestNG (with DataProvider)
* **BDD Framework:** Cucumber (Java + TestNG)
* **Build & Dependencies:** Maven, WebDriverManager (Bonigarcia)
* **Reporting:** ExtentReports (HTML reports with automatic failure screenshots)
* **AI Tool Integration:** GitHub Copilot Agent mode (used for script refactoring and test optimization).

---

## 3. Project Folder Structure
```text
CubeCartAutomationFramework
├── .github/agents        -> GitHub Copilot Agent configuration files
├── src/main/java         -> Base classes, Page Object classes, Utilities, ConfigReader
├── src/test/java         -> TestNG test classes, Listeners, Cucumber Runners, Step Definitions
├── src/test/resources    -> Cucumber .feature files
├── config.properties     -> Stores AUT URLs and credentials externally
├── pom.xml               -> Maven project configuration & dependencies
├── testng.xml            -> TestNG suite configuration file
└── README.md
