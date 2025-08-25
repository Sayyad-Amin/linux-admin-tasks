# 📝 Task 02 – Create a User with a Non-Interactive Shell

## 📌 Objective
Create a Linux user that cannot log in interactively (no shell access).  
This is commonly used for **service accounts**, **automation users**, or **restricted system users**.

---

## 🛠 Steps

### 1. Create a user with `/sbin/nologin` shell
```bash
sudo useradd -s /sbin/nologin shehzad
