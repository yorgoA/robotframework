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
├── data/                   # Test data files
├── external-keywords/      # Custom Python keyword libraries
├── resources/              # Shared keywords, locators, and utilities
├── tests/                  # Test suites (web + mobile)
├── rfenv/                  # Virtual environment (ignored by Git)
├── requirements.txt        # Python dependencies
└── .gitignore              # Ignore unnecessary files/folders
```

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
