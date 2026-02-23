<div align="center">

# 🌐 DataSphere 
## Social Media Database Management System

A **Python + MySQL + Tkinter** project that manages social-media-style data — users, posts, comments through a simple graphical interface. It implements **database connectivity**, **CRUD operations**, and **GUI programming** in Python! 🚀

</div>

## 📖 Project Overview

This application demonstrates how to build a full **CRUD-based Social Media Database Management System** using:

- **Tkinter** for the frontend GUI  
- **MySQL** as the persistent backend database  
- **Python** to connect everything together  

It handles users, posts, and comments with proper relationships — ideal for college projects, database learning, or mini social-media prototypes.

## ✨ Key Features

- ✅ **Create** new users, posts, and comments via GUI  
- 👀 **View** / list records in clean tabular or list format  
- ✏️ **Update** existing records (if implemented)  
- 🗑️ **Delete** users/posts/comments safely  
- 🔗 Proper relational database schema (users ↔ posts ↔ comments)  
- 🖥️ Simple, intuitive **Tkinter** interface  
- 🗄️ All data is **persistently stored** in MySQL  

## 🛠️ Tech Stack

| Technology       | Purpose                          | Version / Notes                  |
|------------------|----------------------------------|----------------------------------|
| 🐍 **Python**    | Core programming language        | 3.x (recommended)                |
| 🖼️ **Tkinter**   | Native GUI framework             | Built-in with Python             |
| 🗄️ **MySQL**     | Relational database backend      | MySQL Server / MariaDB compatible|
| 🐬 **mysql-connector-python** | Python ↔ MySQL connector   | pip install mysql-connector-python |
| 📊 **Tabular display** | Treeview (Tkinter) for showing records | Built-in Tkinter widget     |


## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/RheyaRajesh/DataSphere.git
   cd DataSphere

2. Install MySQL connector
   ```bash
   pip install mysql-connector-python

3. Set up MySQL database
  - Create a database (e.g. social_media_db)
  - Run the schema creation code (likely in schema.py)

4. Run the application
   ```bash
   python frontend.py
