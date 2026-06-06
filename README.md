<div align="center">

# 🐚 Bash User Management System

**A menu-driven, automated administrative tool for Linux system management.**

![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📋 Project Overview
This project provides an automated, text-based interface to perform essential Linux system administration tasks. By leveraging Bash scripting and the `dialog` utility, this tool simplifies user and group management, reducing the complexity of command-line operations into an intuitive, menu-driven experience.

## 🛠️ Key Functionalities
The system provides centralized control for local system management:

* **User Lifecycle Management:** Add, modify, delete, and list system users with ease.
* **Account Security:** Instant lock (disable) and unlock (enable) capabilities for user accounts.
* **Group Administration:** Create, modify, and delete user groups to maintain organized access control.
* **Credential Management:** Quickly update user passwords via an automated interface.

---

## 🖥️ System Interface
The tool uses a clean, menu-based structure to ensure ease of navigation for system administrators.

![Main Menu](INSERT_IMAGE_LINK_HERE)

---

## ⚙️ How it Works
The Bash User Management System interacts directly with the Linux system’s identity files and commands:
* **Automation:** Wraps standard `useradd`, `usermod`, `userdel`, `groupadd`, and `passwd` commands into a single script.
* **Validation:** Includes error handling to ensure users exist before modifications and validates password requirements.
* **Interface:** Utilizes the `dialog` utility to generate professional, interactive forms and alerts.

---

## 👥 Developed By
**Mohamed Morsi Saad Saeed**
*System Administration Track — ITI Alexandria*

---

<div align="center">

*Streamlining Linux administration through automation.*

</div>
