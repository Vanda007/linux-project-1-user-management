# 🐧 User & Permission Management (Linux Sysadmin Simulation)

## 📌 Deskripsi
Project ini mensimulasikan tugas seorang System Administrator dalam mengelola user, folder, serta permission pada sistem Linux.

Environment menggunakan WSL (Windows Subsystem for Linux) sehingga dapat meniru server Linux secara lokal.

---

## 🖥️ Environment
- OS: Windows 11
- Virtual Environment: WSL (Windows Subsystem for Linux)
- Linux Distro: Ubuntu

---

## 🎯 Tujuan
- Membuat dan mengelola user
- Mengatur hak akses (permission)
- Mensimulasikan skenario kerja di server Linux

---

## ⚙️ Langkah-Langkah

### 1. Membuat User
```bash
sudo useradd -m -s /bin/bash developer
sudo useradd -m -s /bin/bash tester
