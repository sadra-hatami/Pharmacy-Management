<div align="center">

# Pharmacy Management
# 💊

### A C++ console desk for medicine orders and receipts

A small terminal pharmacy: take an order, edit it, print a receipt, and see the day's sales. Orders stay in memory for the current run.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Console](https://img.shields.io/badge/Interface-Console-2C3E50?style=for-the-badge)](https://en.wikipedia.org/wiki/Command-line_interface)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/license/mit)
![Open Source](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Email](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Project?](#-why-this-project)
- [Key Features](#-key-features)
- [Menu](#-menu)
- [Project Structure](#-project-structure)
- [Technologies](#️-technologies)
- [Build](#-build)
- [Usage](#️-usage)
- [Notes](#-notes)
- [FAQ](#-faq)
- [Contact](#-contact)
- [License](#-license)
- [Support](#-support)

---

# 📖 About

**Pharmacy Management** is a console program written in C++.

The desk takes a medicine order, stores it in a linked list, and can delete, modify, or print that order. A receipt shows the lines and the total. A daily summary adds up the orders still in memory.

Medicine names and prices are built into the program. Each order can hold up to ten lines. Closing the program clears the list.

> **Tagline:** *A C++ console desk for medicine orders, receipts, and a daily sales summary.*

---

# 🚀 Why This Project?

A pharmacy menu is a clean place to practice a linked list and a bill.

This one keeps that scope:

- A new order with customer name, date, and quantities
- Delete and modify by receipt number
- A printed receipt and a payment step
- A daily total of the orders still stored

It is a study program, not a pharmacy system.

---

# ✨ Key Features

- 💊 Take a new medicine order
- 🗑️ Delete an order by receipt number
- ✏️ Modify customer, date, or quantities
- 🧾 Print a receipt and take payment
- 📊 Daily summary of stored sales
- 💻 Console menu only

---

# 🎮 Menu

1. Take new Medicine order
2. Delete latest Medicine order
3. Modify Order List
4. Print the Receipt and Make Payment
5. Daily Summary of total Sale
6. Exit

An order keeps a receipt number, customer name, date, selected medicines, quantities, line amounts, and a total.

---

# 📁 Project Structure

```text
Pharmacy-Management/
├── Pharmacy_Management.cpp
└── README.md
```

`Pharmacy_Management.cpp` is the program. Do not commit a compiled `.exe`.

---

# 🛠️ Technologies

- C++
- Standard library streams and strings
- A singly linked list for orders
- No database and no extra packages

---

# 🚀 Build

```bash
git clone https://github.com/sadra-hatami/Pharmacy-Management.git
cd Pharmacy-Management
g++ Pharmacy_Management.cpp -o pharmacy
./pharmacy
```

On Windows, MinGW can build the same file.

---

# ▶️ Usage

1. Build and run.
2. Take a new order and pick medicines.
3. Print the receipt, or open the daily summary.
4. Exit when the desk is done.

---

# 📝 Notes

- Orders are in memory only. A restart clears them.
- The medicine list and prices are fixed in the source file.
- The repository should hold source and this README, not the binary or the original archive.
- This is a practice desk, not a real pharmacy or a medical service.

---

# ❓ FAQ

### Does it save orders?

No. The linked list is cleared when the program exits.

### Can the medicine list be edited from the menu?

No. Names and prices are set in the program.

### Is this a website?

No. It is a terminal menu.

---

# 📬 Contact

**Developer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If this program is useful as a study sample, please consider giving it a ⭐ on GitHub.

---

<div align="center">

## Designed & Developed with ❤️ for the developer community of Iran and the world by **Sadra Hatami**

</div>
