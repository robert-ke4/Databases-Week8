# Databases Week 8: MySQL Backup and Recovery

This repository contains the submission for the Databases Week 8 assignment on MySQL backups using `mysqldump`, based on the `sales` database schema and dataset (`salesdb_2.sql`).

## Contents

- `answers.sql` — SQL-commented commands and explanations for the backup tasks.
- `salesdb_2.sql` — Reference SQL script that creates and populates the `sales` database (`productlines`, `products`, `offices`, `employees`, `customers`, `payments`, `orders`, and `orderdetails`).
- `README.md` — Documentation, usage instructions, and notes on the assignment.

## Commands Summary

1. **Complete backup of the `sales` database** (`sales_backup.sql`):
   ```bash
   mysqldump -u root -p sales > sales_backup.sql