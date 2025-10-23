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
```
### **⚡ Установка Git**
```bash
# 🐧 Linux/Ubuntu
sudo apt install git

# 🪟 Windows (winget)
winget install --id Git.Git -e --source winget
```

### **⚙️ Базовая конфигурация**

| Настройка | Значение | Описание |
|-----------|----------|----------|
| **Редактор** | `VIM` | Редактор по умолчанию |
| **Ветка** | `main` | Основная ветка по умолчанию |
| **Конфиг** | `C:\Program Files\Git\etc\gitconfig` | Глобальный файл настроек |
| **Документация** | `man git` | Руководство пользователя |

## 🛠️ Основные команды Git

### **📁 Создание и клонирование репозитория**

```bash
# Клонирование удаленного репозитория
git clone <URL_remote_repository>
```

### **📝 Работа с файлами**

```bash
# Создание нового файла
echo "create new file" > filename.txt

# Проверка статуса
git status
```

### **✅ Создание коммита**
```bash
# Добавление файлов в staging area
git add <filename>        # Конкретный файл
git add .                 # Все файлы

# Создание коммита с сообщением
git commit -m "📝 Ваше сообщение коммита"
```

### **📤 Отправка изменений**
```bash
# Просмотр подключенных удаленных репозиториев
git remote -v

# Отправка изменений в удаленный репозиторий
git push origin main
```

### **👤 Настройка пользователя**
```bash
# Глобальная настройка имени и email
git config --global user.name "AlexeyLitovchenko"
git config --global user.email "algaritmno822@gmail.com"
git config --global core.editor "vim"
```
## 📚 Домашнее задание

### **🎯 Цель задания:**
Освоить процесс работы с Fork и Pull Request в GitHub

### **📋 Задачи:**

#### **1. FORK репозитория 🔗 [Mathematics Repository](https://github.com/AlexeyTri/Mathematics)**
#### **2. в ветку new_feature добавить файл file_your_family, файл может содержать любую полезную информацию **
#### **3. выполнить pull_request данного репозитория **
#### **4.https://docs.github.com/ru/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo**

## **🎮 Тренажер для Git**

<div align="center">
💪 Практикуйте свои навыки работы с Git!
https://img.shields.io/badge/Play-Git_Mastery-blue?style=for-the-badge&logo=git

🔗 Ссылка: https://www.gitmastery.me/playground

</div>

