## 📁 Project Structure

```
project-root/
│
├── data/                   # Test data for specific groups
├── external-keywords/      # Custom Python keyword libraries
├── resources/              # Test data for common locators
│   ├── keywords/           # Reusable Robot Framework keywords
│   ├── locators/           # Web element locators (by page)
│   └── variables.robot     # Global test variables
├── tests/
│   ├── web/                # Web UI test suites
│   └── mobile/             # Mobile test suites (future)
├── reports/                # Test execution reports
├── rfenv/                  # Virtual environment (ignored by Git)
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── .gitignore              # Ignore unnecessary files/folders
```
