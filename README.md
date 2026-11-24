# Pet Management System

A Python and MySQL-based console application for managing pets, pet accessories, customer accounts, and orders.

## Features
* **User Portal:** Register, log in, view/update profile, search and browse available pets and accessories, place orders, and view order history.
* **Admin Portal:** Add, update, delete, and view users, pets, and pet accessories, plus check overall shop statistics.

## Prerequisites
* Python 3.x
* MySQL Server

## Setup Instructions
1. Install the required MySQL connector:
   ```bash
   pip install -r requirements.txt
Open MySQL and create the database:

SQL
CREATE DATABASE pet_management;
(All required tables—customers, pets, pet_accessories, and user_orders—are created automatically when you run the script.)

Open pet_management.py and update the MySQL user and password at the top of the file to match your local MySQL setup.

How to Run
Bash
python pet_management.py
Default Admin Login
Username: ADMIN
Password: 12345


