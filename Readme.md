# 🚀 Git Mastery Guide

![Git Logo](https://git-scm.com/images/logo@2x.png)

## 📥 Установка и настройка Git

### **Скачивание Git**
<div align="center">

[![Download Git](https://img.shields.io/badge/Download-Git-orange?style=for-the-badge&logo=git)](https://git-scm.com/downloads)

</div>

### **🔄 Удаление Git**
```bash
# 🐧 Linux/Ubuntu
sudo apt-get purge git

# 🪟 Windows (PowerShell)
Get-ChildItem -Path "C:\Program Files\Git" -Filter "unins00*.exe" -Recurse | ForEach-Object { & $_.FullName }
