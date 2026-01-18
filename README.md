# 🏎️ Urban Routes: Final Automation Capstone Project (E2E)

## 📝 Project Overview

This is my graduation project from the QA Bootcamp. I developed a complete End-to-End (E2E) Automation Suite for the Urban Routes platform. The project covers the entire user journey, from entering addresses to the final booking confirmation, ensuring that all functional modules work together seamlessly.

## 🏗️ Architecture: Page Object Model (POM)

I implemented the **Page Object Model (POM)** design pattern to build a scalable and maintainable automation framework. This approach separates the page-specific elements from the actual test logic, resulting in:

* **High Maintainability:** UI changes only require updates in one place.
* **Code Reusability:** Methods can be shared across multiple test scenarios.
* **Readability:** Tests are written in clear, logical steps that anyone can follow.

## 🎯 Technical Skills Applied

- **Page Objects:** Created dedicated classes for each page of the application.
- **Advanced Locators:** Used optimized CSS Selectors and XPaths for stable element detection.
- **Method Composition:** Combined basic actions into complex methods (e.g., "Full Booking Process") to streamline test scripts.
* **Test Hooks:** Utilized setup_class() for driver initialization and teardown_class() for clean browser exits.
- **Wait Strategies:** Implemented explicit waits to handle dynamic web elements and prevent "flaky" tests.

## 🗺️ Planning & Strategy
Before writing the first line of code, I mapped out the application logic to ensure total test coverage.

**Project Mind Map**
https://drive.google.com/file/d/18vA-vnK74hV6TRKWICijZHp14VlXsow5/view?usp=sharing

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Automation:** Selenium WebDriver
* **Testing Framework:** Pytest
* **Logic Pattern:** Page Object Model (POM)

## 📂 Project Deliverables

* Full Documentation (6-Sheet Report): Detailed test design, checklists, and execution logs. https://docs.google.com/spreadsheets/d/1tgm1U_2mU58A_5jcfU8cAyzXbE80wE-v/edit?usp=sharing&ouid=110641800876252641675&rtpof=true&sd=true

* Automation Scripts: Located in the **/tests** folder of this repository.

## 🚀 How to Run the Suite

1. Clone this repository.
2. Install dependencies: pip install -r requirements.txt.
3. Run the tests: pytest main.py.

## 🌍 Language Notice
[!NOTE] Documentation Language Notice

While the automation code and this README are in English, the supporting technical documentation (test cases and checklists) was originally delivered in Spanish to meet the bootcamp's requirements. I have maintained the original language of those documents to preserve the authenticity of the project delivery.
