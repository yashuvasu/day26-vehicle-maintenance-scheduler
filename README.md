# 🚗 Day 26 – Vehicle Maintenance Scheduler

A C program that helps users track vehicle maintenance schedules based on odometer readings.

## 📌 Overview

Regular maintenance improves vehicle performance, safety, and fuel efficiency. This project checks whether different maintenance tasks are due based on the current odometer reading.

## ⚙️ Features

- Engine oil reminder
- Brake inspection reminder
- Air filter replacement reminder
- Coolant service reminder
- Battery health check
- Service status dashboard

## 🧠 Logic

The program compares the current odometer reading with the last service mileage and calculates whether each maintenance task is:

- ✅ OK
- ⚠ Due Soon
- 🔴 Service Due

## 🛠 Tech Stack

- C Programming
- GCC Compiler
- Ubuntu/Linux

## ▶️ How to Run

```bash
gcc maintenance_scheduler.c -o scheduler
./scheduler# day26-vehicle-maintenance-scheduler
A C-based Vehicle Maintenance Scheduler that tracks odometer readings and reminds users when services like engine oil change, brake inspection, and air filter replacement are due.
