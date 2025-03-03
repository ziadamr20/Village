# Village Management System - Automation Testing

## Overview
This repository contains an **Automation Testing Framework** for the **Village Management System**, developed using **Selenium WebDriver** and **TestNG**. It ensures the system's reliability by automating critical test scenarios and verifying functionality across different browsers.

## Features
- **Cross-browser testing** (Chrome, Firefox, Edge)
- **Test execution using TestNG**
- **Page Object Model (POM) implementation**
- **Data-driven testing using Excel/CSV**
- **Logging & Reporting with Extent Reports/Allure Reports**
- **CI/CD integration (GitHub Actions/Jenkins)**

## Technologies Used
- **Programming Language**: Java
- **Testing Framework**: TestNG
- **Build Tool**: Maven
- **Dependency Management**: Maven (pom.xml)
- **Reporting**: Extent Reports / Allure Reports
- **Version Control**: Git & GitHub
- **CI/CD**: Jenkins / GitHub Actions

## Installation & Setup
### Prerequisites
- **Java 8+**
- **Selenium WebDriver** installed
- **Maven** installed
- **TestNG** installed
- **Browser Drivers** (ChromeDriver, GeckoDriver, EdgeDriver)

### Clone the Repository
```sh
   git clone https://github.com/ziadamr20/Village.git
   cd village-management-automation
```

### Install Dependencies
```sh
  mvn clean install
```

### Run Tests
```sh
  mvn test
```

## Framework Structure
```
village-management-automation/
│── src/
│   ├── test/java (Test Cases)
│   ├── main/java (Page Objects & Utilities)
│── reports/ (Test Reports)
│── resources/ (Test Data, Configs)
│── pom.xml (Maven Project)
│── README.md
```

## Reporting & Logs
- **Extent Reports**
- **Allure Reports**
- **Console logs for debugging**

## Continuous Integration (CI/CD)
- **Jenkins Pipeline Setup**
- **GitHub Actions Workflow**
- **Dockerized Selenium Grid for Parallel Testing**

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```sh
   git commit -m "Added new test case"
   ```
4. Push the branch:
   ```sh
   git push origin feature-name
   ```
5. Open a Pull Request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For queries, contact:
- **Email**: ziadamr200@gmail.com
- **GitHub**: [ziadamr20](https://github.com/ziadamr20)

