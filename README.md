# 🚗 Parking Management System

A simple C-based console application to manage vehicle parking operations for cars and bikes. This system keeps track of parked vehicles, their details, and allows users to back up data into files.

---

## 🛠️ Features

- 🚙 Add new vehicles (Car or Bike)
- 📊 View total number of parked vehicles
- 🚘 View individual counts for cars and bikes
- 📋 Display order of parked vehicles
- ❌ Remove vehicles from the parking
- 💾 Backup vehicle data to text files
- 🧾 Basic console-based interface

---

## 🧾 File Output

Data is backed up in two files:
- `PARKING_DATA_CAR.txt` – List of parked cars with registration number and CNIC
- `PARKING_DATA_BIKE.txt` – List of parked bikes with registration number and CNIC

> ⚠️ Make sure to change the file path in the code (`fopen`) to a valid directory on your system to avoid file errors.

---

## 🧑‍💻 Authors
- Syed Hammad Alam – 22K-4675  
---

## 💻 Requirements

- Windows OS (uses `conio.h`, `windows.h`)
- C Compiler (e.g., Turbo C, Dev C++, GCC with compatibility setup)

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/parking-management-system.git
   ```

2. Compile the C program:
   ```bash
   gcc "PROJECT PARKING MANAGEMENT.c" -o parking.exe
   ```

3. Run the executable:
   ```bash
   ./parking.exe
   ```

> Make sure your terminal supports Windows-based C libraries (`conio.h`, `windows.h`) or use an IDE like Turbo C++.

---

## 📌 Notes

- Only supports up to 20 cars and 20 bikes at once.
- Designed for educational/demo purposes. For production, consider using databases and modern UI.

---
