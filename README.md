# Practical 7 — SQLite + JSON Person Manager App

A simple Android application that demonstrates **SQLite database operations** and **JSON API integration** for managing person data in a combined list.

---

##  Features

###  View Data (SQLite + JSON API Combined)
- Loads person data from:
  - Local SQLite database
  - Remote / mock JSON API
- Merged into a **single RecyclerView list**

###  Add Person
Users can add:
- Name  
- Email  
- Phone  
- Address  

New entries are saved into **SQLite**.

###  Delete Person
- **SQLite entries** → removed from database  
- **JSON entries** → removed from list only  
- Maintains data integrity  

###  Auto Refresh
List automatically updates when returning to the main screen.

---

##  How It Works

### **MainActivity**
- Loads persons from:
  - SQLite (local DB)
  - JSON API (remote or mock)
- Displays list in RecyclerView with:
  - Name
  - Phone
  - Email
  - Address
  - Pink delete button
- "Register" button → navigates to the **Registration screen**

---

#  OUTPUT

### Screenshot
![output](https://drive.google.com/uc?export=view&id=1vov_7_eWOHyTT1RwJbdZUdsGP6E7gSLQ)

---

##  Summary

This practical demonstrates:
- SQLite CRUD operations  
- Fetching & combining JSON API data  
- RecyclerView with dynamic data updates  
- Database + network integration  
- Clean architecture using multiple data sources  

A complete Person Manager app built using Android + Kotlin.

