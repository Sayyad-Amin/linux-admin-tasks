# 📝 Task 01 – Create a User with an Expiry Date

## 📌 Objective
Create a new Linux user account that automatically expires after a specified date.  
This is useful in scenarios like **temporary access for interns, contractors, or project-based accounts**.

---

## 🛠 Steps

### 1. Create user with expiry date
Use the `-e` option with `useradd`:
```bash
sudo useradd -e YYYY-MM-DD username

sudo useradd -e 2025-12-31 temp-user
