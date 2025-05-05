# Validate South African ID Number

This Java project validates South African ID numbers using a Test-Driven Development (TDD) approach. It includes a command-line interface and adheres to best practices for clean, testable code.

## 📋 Project Overview

A valid South African ID number must:
- Be exactly **13 digits** long.
- Follow the format: `YYMMDDSSSSCAZ`:
  - **YYMMDD** – birth date.
  - **SSSS** – gender code (0000–4999 female, 5000–9999 male).
  - **C** – citizenship status (`0` for citizen, `1` for permanent resident).
  - **Z** – checksum digit (Luhn algorithm).

## 🔧 Tech Stack

- **Language:** Java
- **Build Tool:** Gradle
- **Testing Framework:** JUnit

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/validate_sa_id.git
cd validate_sa_id
2. Initialize and build the project
bash
Copy
Edit
./gradlew build
3. Run the application
bash
Copy
Edit
./gradlew run
4. Run the tests
bash
Copy
Edit
./gradlew test
📂 Project Structure
bash
Copy
Edit
validate_sa_id/
│
├── build.gradle             # Gradle build configuration
├── settings.gradle          # Gradle settings
└── src/
    ├── main/
    │   └── java/
    │       └── org/example/
    │           ├── App.java               # Command-line interface
    │           └── ValidateSaId.java      # Core validation logic
    └── test/
        └── java/
            └── org/example/
                └── ValidateSaIdTest.java  # Unit tests (you write these!)
✅ Validation Rules
The following checks are performed:

✔️ Length check (13 digits)

✔️ Digit-only check

✔️ Date of birth (YYMMDD) is valid

✔️ Gender range (optional enhancement)

✔️ Citizenship digit is either 0 or 1

✔️ Checksum using the Luhn Algorithm

🧪 Test-Driven Development (TDD)
This project follows the RED, GREEN, REFACTOR cycle:

RED – Write a failing test

GREEN – Write code to pass the test

REFACTOR – Improve the code while ensuring tests still pass

Write meaningful Git commits after each test passes.

📚 Resources
Java Unit Testing Best Practices – Baeldung

JUnit Tutorial – Coding with John

✍️ Author
Tiyani Confidence Nyathi

📄 License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

Would you like help generating unit tests for `ValidateSaId` using JUnit?







