# MediTrack - Hospital Management System

**A Modern Hospital Management System with Role-Based Access & Real-Time Sorting Algorithm Comparison**

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Tkinter](https://img.shields.io/badge/Tkinter-GUI-4CAF50?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/library/tkinter.html)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

Live Demo Video (1 min) • 100% Working Project • Ready for Submission

## Project Preview


| Login Screen                 | Admin Dashboard                 | Appointment Booking             |
|-----------------------------|----------------------------------|----------------------------------|
| ![Login](assets/login.png)  | ![Admin](assets/admin.png)      | ![Booking](assets/booking.png)  |

| Patient Medical Records (HeapSort) | Sorting Algorithms Graph |
|-------------------------------------|---------------------------|
| ![Records](assets/records.png)      | ![Graph](assets/graph.png) |

## Features That Will Impress Everyone

| Feature                            | Description |
|------------------------------------|-------------|
| 3 User Roles                      | Admin • Doctor • Patient |
| Secure Login & Registration       | Email + Password |
| Appointment Booking               | Real-time clash detection |
| Medical Records with Sorting      | Custom **HeapSort** (Asc/Desc) |
| Live Algorithm Benchmarking       | QuickSort • MergeSort • HeapSort |
| Automatic Performance Graph       | Matplotlib visualization |
| Pre-loaded Database               | 50 Patients • 15 Doctors • 60+ Appointments |
| Clean Modern GUI                  | Themed with `clam` style |

## Tech Stack

- **Frontend** → Python + Tkinter + ttk
- **Backend** → MySQL
- **Visualization** → Matplotlib
- **Algorithms** → Hand-coded QuickSort, MergeSort, HeapSort
- **Database** → 5 tables with foreign keys

## How to Run (Takes Only 2 Minutes)

```bash
# 1. Clone repo
git clone https://github.com/YOUR_USERNAME/MediTrack-Hospital-Management-System.git
cd MediTrack-Hospital-Management-System

# 2. Install requirements
pip install -r requirements.txt

# 3. Setup Database
#    Create database named: jani
mysql -u root -p -e "CREATE DATABASE jani;"
mysql -u root -p jani < medi_track_database.sql

# 4. Update password in main.py (line ~30)
#    password = "your_mysql_root_password"
