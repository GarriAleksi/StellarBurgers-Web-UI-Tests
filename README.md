# 
Test coverage includes:
✔ User flows: Registration, login (4 methods), logout
✔ Navigation: Personal account ↔ Constructor, section switching (Buns/Sauces/Fillings)
✔ Validation: Password rules (min 6 chars)

Tech stack:

Java 11

Selenium WebDriver

JUnit 5

Allure Reports

Page Object Pattern

Key features:

Cross-browser testing (Chrome/Yandex Browser)

API-precondition setup for test users

@Step-annotated Allure reports

Clean test isolation with pre/post conditions

Implementation notes:

Locators follow business naming conventions

Each page has dedicated Page Object class

PR includes Allure results (target/allure-results)
