# Hash_Table_Fundamentals_and_Implementation

## Overview

This project contains implementations of **10 practical problems based on Hash Tables**.
All problems are implemented in **a single Java file (`Main.java`)** with **hardcoded sample inputs** to demonstrate the functionality.

The goal of this assignment is to understand how **HashMaps and hash-based data structures** are used in real-world systems such as social media platforms, e-commerce systems, caching systems, and analytics dashboards.

---

## Technologies Used

* **Java**
* **HashMap**
* **Array-based hashing**
* **Basic data structures**

---

## Problems Implemented

### 1. Social Media Username Availability Checker

* Checks username availability in **O(1)** time.
* Suggests alternative usernames.
* Tracks attempted usernames.

### 2. E-commerce Flash Sale Inventory Manager

* Tracks product stock in real time.
* Prevents overselling during flash sales.
* Demonstrates instant inventory lookup.

### 3. DNS Cache with TTL

* Simulates a **domain-to-IP caching system**.
* Demonstrates cache hits and misses.

### 4. Plagiarism Detection System

* Uses **hash tables to store n-grams**.
* Helps detect similar documents.

### 5. Real-Time Website Analytics Dashboard

* Tracks page visits.
* Displays most visited pages.

### 6. Distributed Rate Limiter

* Limits API requests per client.
* Demonstrates request tracking using HashMap.

### 7. Search Engine Autocomplete System

* Stores search queries and frequency counts.
* Returns popular suggestions.

### 8. Parking Lot Management (Open Addressing)

* Assigns parking spots using a **hash function**.
* Uses linear probing for collision handling.

### 9. Two-Sum Financial Transaction Detection

* Finds transactions that sum to a target value.
* Uses HashMap for **O(1) lookup**.

### 10. Multi-Level Cache System

* Simulates **L1 and L2 cache layers**.
* Demonstrates cache hit and miss logic.

---

## Project Structure

```
HashTableAssignment
│
├── Main.java
└── README.md
```

---

## How to Run the Program

### Step 1: Compile the program

```
javac Main.java
```

### Step 2: Run the program

```
java Main
```

---

## Sample Output

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

## Concepts Covered

* Hash Tables
* HashMap Implementation
* O(1) Lookup
* Collision Handling
* Frequency Counting
* Caching Techniques
* Real-world System Design

---

## Author

**Nikhil Kumar**

---
