# AlgoExpert Infrastructure Course – Bash & SQL Problems

This repository contains my solutions to the Bash and SQL challenges from the **AlgoExpert Infrastructure Course**. These problems are designed to improve practical scripting and querying skills for working with real infrastructure systems.

---

## 🧩 Bash Problems

### 1. Diskspace Usage
Write a script that calculates the total disk usage of a given directory and displays it in a human-readable format.

### 2. Check If Website Is Up 
Write a Bash script that checks if a website is up by performing a curl request and checking the HTTP status code.

### 3. Count Files
Create a script that counts how many files (not directories) exist in the current directory.

### 4. Hostname
Write a script that prints the hostname of the system it's running on.

### 5. Netstat Routing
Use the `netstat` or equivalent command to list the routing table of the system.

---

## 🧩 SQL Problems

### 1. Average Salary
Write an SQL query to calculate the average salary from a table of employees.

### 2. First Name 
Write an SQL query that selects only the `first_name` column from the `users` table.

### 3. Greater Price
Write a query to return all products with a price greater than a specified value.

### 4. Last 3 Records
Fetch the last 3 records (based on insertion order or a timestamp) from a table.

### 5. Top 10 Customers
Return the top 10 customers with the highest total purchases from a transactions or orders table.

---

## 📁 Structure

```
.
├── bash/
│   ├── check_if_website_is_up.sh
│   ├── diskspace_usage.sh
│   ├── count_files.sh
│   ├── hostname.sh
│   └── netstat_routing.sh
├── sql/
│   ├── first_name.sql
│   ├── average_salary.sql
│   ├── greater_price.sql
│   ├── last_3_records.sql
│   └── top_10_customers.sql
└── README.md
```

---

## 🛠️ How to Run

### Bash Scripts
```bash
chmod +x script.sh
./script.sh
```

### SQL Queries
Run queries using any standard SQL engine (e.g., MySQL, PostgreSQL, SQLite).

---
