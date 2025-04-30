# South African ID Validator

A Java application that validates South African ID numbers (13 digits) with detailed error reporting.

## Features
- ✅ **Length & Format**: Validates 13-digit numeric format  
- 📅 **Date Validation**: Checks YYMMDD birth date (including leap years)  
- 🛂 **Citizenship Check**: Verifies digit 11 is 0 or 1  
- 🔢 **Luhn Checksum**: Validates using modulus-10 algorithm  
- ❌ **Detailed Errors**: Lists all validation failures  

## Getting Started

### Prerequisites
- Java 11 or higher
- Gradle (optional, for building)

### Installation
1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd south-african-id-validator
