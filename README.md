# 📚 BookNest – Library Management System

## 📖 Project Overview

**BookNest** is a Library Management System developed using Python and Flask to simplify and manage library operations. The application helps librarians manage books, register students, issue books, and track return records efficiently.

The project also includes a Streamlit-based analytics dashboard that provides insights into library activities, including book availability, student registrations, and borrowing records.

## 🎯 Objectives

- Manage library books efficiently.
- Register and maintain student information.
- Issue books to registered students.
- Track book returns and availability.
- Provide library activity analytics.
- Reduce manual work in library management.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| SQLite | Database management |
| HTML | Web page structure |
| CSS | Web page styling |
| Streamlit | Analytics dashboard |
| Pandas | Data analysis |

## ✨ Features

- 📚 Book Management
- 👨‍🎓 Student Registration
- 📕 Book Issue Management
- 🔄 Book Return Management
- 🔍 Search Books
- 📊 Library Analytics Dashboard
- 🗄️ SQLite Database Integration

## 📂 Project Structure

```text
BookNest/
│
├── app.py
├── database.py
├── library.db
├── analytics.py
│
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── books.html
│   ├── students.html
│   ├── issue_book.html
│   └── issue_records.html
│
├── static/
│   └── style.css
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/BookNest.git
```

### 2. Navigate to the Project Folder

```bash
cd BookNest
```

### 3. Install Required Packages

```bash
pip install flask pandas streamlit
```

### 4. Run the Flask Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

### 5. Run the Analytics Dashboard

```bash
streamlit run analytics.py
```

## 🗄️ Database

BookNest uses SQLite to store and manage library information.

The database contains the following tables:

- **Books:** Stores book details such as title, author, category, quantity, and availability.
- **Students:** Stores student information such as name, department, and email.
- **Issue Records:** Maintains book issue dates, return dates, and borrowing status.

## 🚀 Future Enhancements

- User authentication and login system.
- Fine calculation for overdue books.
- Email notifications for due dates.
- Advanced book search functionality.
- Improved analytics and visualization.
- Online book reservation system.

## 👩‍💻 Developed By

**Janani Kumar**

B.Tech – Information Technology

## 📌 Project Type

Academic Project | Library Management System

## 📄 License

This project is developed for educational purposes.
# library-management-system
