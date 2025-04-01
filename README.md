# SIT737 Task 4.2C – Enhanced Calculator Microservice

## 📘 Overview

This project extends the calculator microservice from Task 4.1P by:

- Adding **advanced operations**: exponentiation, square root, and modulo
- Integrating **Winston logging** for monitoring
- Documenting **microservice error-handling strategies** in a report

---

## ✨ Features

| Endpoint    | Description                        | Example Query              |
| ----------- | ---------------------------------- | -------------------------- |
| `/add`      | Adds two numbers                   | `/add?num1=5&num2=2`       |
| `/subtract` | Subtracts second number from first | `/subtract?num1=10&num2=4` |
| `/multiply` | Multiplies two numbers             | `/multiply?num1=3&num2=7`  |
| `/divide`   | Divides first number by second     | `/divide?num1=10&num2=2`   |
| `/power`    | Exponentiation: num1 ^ num2        | `/power?num1=2&num2=3`     |
| `/sqrt`     | Square root of num1                | `/sqrt?num1=16`            |
| `/modulo`   | Modulo: num1 % num2                | `/modulo?num1=10&num2=3`   |

---

## 🛠️ How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bowen159yao/sit737-2025-prac4c.git
   cd sit737-2025-prac4c
   ```
