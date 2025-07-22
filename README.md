# 🧑‍💼 Bulk AD User Creator

This script automates the creation of Active Directory user accounts from a structured CSV file. It supports specific Organizational Units (OUs), setting passwords when available, and handling missing data. Users without passwords are created in a disabled state by default. 

---

## 📦 Features

- Bulk creation of AD users from CSV input
- OU selection from either the CSV or via override
- Password assignment with automatic handling of empty fields
- Error catch and output for failed user additions
- Minimal dependencies—just the Active Directory module

---

## 📋 Usage Example

Bulk-ADUser-Creator.ps1 -CSV_Path "C:\Scripts\ad-users.csv" -Password_Column_name "password" -Override_OU "OU=NewUsers,DC=contoso,DC=com"

---

## ⚠️ Disclaimer

This script was built for internal use, learning, and practical automation. It’s shared as-is, without guarantees, and may need adjustment before use in production environments. Please review the logic, email settings, and file paths. 
