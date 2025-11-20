# 🤖 Robot Framework Automation Project  
### **Selenium (Web UI) + Appium (Mobile) Test Automation**

This repository showcases my skills in **end-to-end test automation** using **Robot Framework**, covering both web and mobile platforms.

The project demonstrates:
- Web UI automation using **SeleniumLibrary**
- Mobile automation using **AppiumLibrary**  
- A clean project structure with reusable keywords, locators, and variables
- Python virtual environment setup for isolated dependencies

---

## 🚀 Tech Stack

### **Core Framework**
- Robot Framework

### **Web Automation**
- SeleniumLibrary  
- Modern Selenium (Selenium Manager)

### **Mobile Automation (for future expansion)**
- AppiumLibrary  
- Android/iOS automation support

### **Languages & Tools**
- Python  
- VS Code  
- Virtual Environments (venv)

---

## 📁 Project Structure

```
project-root/
│
├── data/                   # Test data for specific test groups
├── external-keywords/      # Custom Python keyword libraries
├── resources/              # Reusable test resources and configuration
│   ├── keywords/           # BDD-style keyword files (Given/When/Then pattern)
│   ├── locators/           # Web element selectors (organized by page)
│   ├── common_test_cases/  # Shared test flows and reusable test scenarios
│   └── variables.robot     # Global test variables and configuration
├── tests/
│   ├── web/                # Web UI test suites
│   └── mobile/             # Mobile test suites (future)
├── selectors/              # Centralized element selector definitions
├── reports/                # Test execution reports and results
├── rfenv/                  # Virtual environment (ignored by Git)
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore              # Ignore unnecessary files/folders
```

## 🎯 Architecture & Testing Approach

### BDD-Inspired Structure

This project follows **behavior-driven development principles** with:
- **Given/When/Then resource files** - Reusable keyword libraries that follow the Given-When-Then pattern for clarity and behavior-driven testing
- **Common test cases** - Shared test flows that eliminate duplication and promote consistent testing patterns across the suite

### Design Principles

**Modular Architecture**: Test logic is separated into reusable components—keywords, locators, and test data—enabling efficient maintenance and scaling.

**Page Object Pattern**: Web element selectors are centralized in `selectors/` and `resources/locators/`, making updates easy and reducing brittle tests.

**Custom Keywords**: Python-based keyword libraries in `external-keywords/` extend Robot Framework capabilities for complex scenarios.

**Data-Driven Testing**: Test cases leverage external data sources for comprehensive coverage across different scenarios.

---

## 🌐 Test Application

This automation suite tests the following web application:

**[DD Demo - Web Elements Testing](https://dd-demo-tau.vercel.app/web_elements.html)**

Visit the link above to explore the web application being automated. The test suite covers various UI interactions including forms, buttons, dropdowns, and other web elements to demonstrate real-world automation scenarios.

---

## 🧪 Running the Tests

### 1️⃣ Activate the virtual environment

```bash
source rfenv/bin/activate
```

### 2️⃣ Install project dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run all Selenium (web) tests

```bash
robot tests/web
```

### 4️⃣ (Later) Run Appium mobile tests

Once Appium is configured:

```bash
robot tests/mobile
```

---

## 🧰 Features Demonstrated

- Browser automation using Selenium
- Page Object–like structure with keyword/resource files
- Clean separation of test data, locators, keywords
- Virtual environment–based dependency isolation
- Ready structure for adding Appium test suites later

## 🎯 Purpose of This Repository

This project serves as a portfolio to demonstrate my skills in:

- Robot Framework
- Selenium test automation
- Appium mobile test automation
- Python-based automation frameworks
- Designing clean, scalable automation structure

## 📜 Future Enhancements

- Add Appium Android and iOS test suites
- Add parallel test execution (Pabot)
- Add CI/CD integration
- Add reporting enhancements and screenshots
