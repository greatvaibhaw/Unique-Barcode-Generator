# 🎯 Unique Barcode Generator

![Java](https://img.shields.io/badge/Built%20With-Java%2010-blue?logo=java)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-lightgrey)
![License](https://img.shields.io/github/license/greatvaibhaw/Unique-Barcode-Generator)

A simple, standalone desktop application to **generate unique barcodes** for products. Built in **Java** with **Oracle** as backend (optional), this tool is perfect for small businesses, shopkeepers, and anyone needing to tag products uniquely in inventory systems like **Tally**.

---

## 📌 Features

- 🔐 Generates **unique barcode values** every time.
- 🖼️ Converts values into **scannable CODE_128 barcode images**.
- 💾 Save barcodes directly as `.png` images on your system.
- 🔁 Optionally integrates with **Oracle 10g** database to store barcode history.
- 📤 Cross-platform support (Windows, macOS, Linux).
- ✅ No internet required – fully **offline tool**.

---

## 📸 Screenshots

> _Note: These are sample placeholders. You can replace them later._

<p align="center">
  <img src="https://github.com/greatvaibhaw/Unique-Barcode-Generator/blob/master/Barcode/assets/Screenshot%202025-07-06%20at%209.19.25%E2%80%AFAM.png" alt="Setting Up Database"/>
  <br/><br/>
  <img src="https://github.com/greatvaibhaw/Unique-Barcode-Generator/blob/master/Barcode/assets/Screenshot%202025-07-06%20at%209.19.41%E2%80%AFAM.png" alt="Application Interface/>
  <br/><br/>
  <img src="https://github.com/greatvaibhaw/Unique-Barcode-Generator/blob/master/Barcode/assets/Screenshot%202025-07-06%20at%209.19.47%E2%80%AFAM.png" alt="Generated View of Barcode"/>
   <br/><br/>
  <img src="https://github.com/greatvaibhaw/Unique-Barcode-Generator/blob/master/Barcode/assets/Screenshot%202025-07-06%20at%209.19.56%E2%80%AFAM.png" alt="Saved View of Barcode"/>
</p>

---

## 🧰 Technologies Used

| Layer         | Tool/Tech                   |
|---------------|-----------------------------|
| Language      | Java 10                     |
| GUI           | Java Swing (AWT)            |
| Barcode API   | ZXing                       |
| Database      | Oracle 10g Express Edition  |
| IDE Used      | NetBeans 8.2                |
| Output Format | PNG                         |

---

## 🏗️ Modules Overview

- `generate()`: Generates a unique string-based barcode value.
- `checkTable()`: Checks and creates the Oracle table if missing.
- `connection()`: Establishes Oracle DB connection via JDBC.
- `getBarcodeImage(String, int, int)`: Converts text into barcode image as `byte[]`.

---

## 📦 Installation & Setup

### 🔧 Requirements

- Java Runtime Environment (JRE 8 or higher)
- (Optional) Oracle 10g XE for database connection

### 🚀 How to Run

```bash
# Navigate to the lib folder
cd lib

# Run the application using Java
java -jar UniqueBarcodeGenerator.jar
