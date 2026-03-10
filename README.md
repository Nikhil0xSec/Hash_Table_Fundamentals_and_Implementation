# Hash Table Fundamentals and Implementation

## Overview

This repository contains implementations of **10 practical problems based on Hash Tables** using **Java**.
The project demonstrates how hash-based data structures are used in real-world systems such as **social media platforms, e-commerce systems, caching systems, analytics dashboards, and search engines**.

All problems are implemented in a **single Java file (`Main.java`)** with **hardcoded sample inputs** to simulate real-world scenarios.

This assignment focuses on understanding:

* Hash Table fundamentals
* O(1) lookup performance
* Collision handling
* Frequency counting
* Real-world system design using hash-based data structures

---

## Technologies Used

* **Java**
* **HashMap**
* **Arrays**
* **Basic Data Structures**
* **Object-Oriented Programming**

---

## Implemented Problems

### 1. Social Media Username Availability Checker

* Checks if a username already exists.
* Suggests alternative usernames.
* Tracks most attempted usernames.

### 2. E-commerce Flash Sale Inventory Manager

* Tracks product stock during flash sales.
* Prevents overselling.
* Handles high-traffic purchase requests.

### 3. DNS Cache with TTL

* Stores domain → IP mappings.
* Demonstrates cache hit and cache miss logic.

### 4. Plagiarism Detection System

* Uses n-grams and hash tables to detect document similarity.

### 5. Real-Time Website Analytics Dashboard

* Tracks page views.
* Displays most visited pages.

### 6. Distributed Rate Limiter

* Limits API requests per client.
* Simulates request throttling using HashMap.

### 7. Autocomplete System for Search Engine

* Stores search queries with frequency counts.
* Suggests popular queries.

### 8. Parking Lot Management System

* Uses hashing to assign parking spots.
* Demonstrates linear probing collision handling.

### 9. Two-Sum Financial Transaction Detection

* Finds transaction pairs that sum to a target value.
* Uses HashMap for O(1) complement lookup.

### 10. Multi-Level Cache System

* Simulates L1 and L2 cache layers.
* Demonstrates cache hits, misses, and promotion logic.

---

## Project Structure

```
Hash_Table_Fundamentals_and_Implementation
│
├── Main.java
└── README.md
```

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/Nikhil0xSec/Hash_Table_Fundamentals_and_Implementation.git
```

### 2. Navigate to the project directory

```
cd Hash_Table_Fundamentals_and_Implementation
```

### 3. Compile the program

```
javac Main.java
```

### 4. Run the program

```
java Main
```

---

## Sample Output

The program prints the results of all 10 problems sequentially.

Example:

```
Problem 1: Username Availability
checkAvailability(john_doe) → false
checkAvailability(jane_smith) → true

Problem 2: Flash Sale Inventory
purchaseItem → Success

Problem 3: DNS Cache
resolve(google.com) → Cache HIT
resolve(yahoo.com) → Cache MISS
```

---

## Key Concepts Demonstrated

* Hash Table Design
* O(1) Lookup Optimization
* Collision Handling
* Frequency Counting
* Caching Systems
* System Design with Hash Maps

---

## Author

**Nikhil Kumar**


---

## License

This project is created for **educational purposes and coursework**.
