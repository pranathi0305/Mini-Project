# 🏏 IPL Database Management System 

An interactive **IPL Database Management System** built using Flask and MySQL, designed to simplify the management of IPL-related data through a user-friendly web interface. The application brings together teams, players, stadiums, matches, and performance statistics in one centralized platform.

With features for viewing, inserting, updating, deleting, and managing records, the project demonstrates the practical application of database management concepts combined with full-stack web development.

## 🚀 Features

- 🔐 **Login System** – Secure access for authorized users  
- 🏠 **Dashboard (Home Page)** – Central hub for navigation  
- 👥 **Player & Team Management** – Add, update, and remove players and teams  
- 🏟️ **Stadium Management** – Manage stadium details  
- 🏆 **Match & Stats** – Record match results and player statistics  
- 📊 **View Page** – Display entire tables with browsing & filtering  
- ➕ **Insert Page** – Add new records through user-friendly forms  
- ✏️ **Update Page** – Edit existing entries  
- ❌ **Delete Functionality** – Remove unwanted or incorrect data  


## 🗂️ Database Schema

The database is normalized into the following main tables:

- **Team** – Team details (name, city, wins, etc.)  
- **Player** – Player details (name, role, country, salary, etc.)  
- **Stadium** – Venue information  
- **Match** – Match details (teams, result, date)  
- **PlayerStats** – Cumulative player performance  
- **MatchStats** – Player stats per match  

👉 SQL schema and sample data are included in the `schema/` folder.


## ⚙️ Tech Stack

- **Backend:** Flask (Python)  
- **Database:** MySQL (via PyMySQL)  
- **Frontend:** HTML, CSS, JS (Bootstrap)  
- **Tools:** MySQL Workbench / phpMyAdmin  


## 📦 Installation

1. **Clone the Repository**
   ```bash
   git https://github.com/akivrooP/Mini-Project
   cd Mini-Project
   ```

2. **Set Up Environment**
   ```bash
   pip install -r requirements.txt
   ```

3. **Database Setup**
   - Create a MySQL database:  
     ```sql
     CREATE DATABASE ipl_db;
     ```
   - Import tables:  
     ```bash
     mysql -u root -p ipl_db < schema/tables.sql
     mysql -u root -p ipl_db < schema/sample_data.sql
     ```

4. **Run the Application**
   ```bash
   python app.py
   ```
   Visit `http://127.0.0.1:5000/` in your browser.

---

## 📊 Dashboard Screens

- **Home Page** – Quick navigation to all features  
- **Login Page** – Secure authentication  
- **Insert Page** – Add new records  
- **Update Page** – Modify existing entries  
- **View Page** – Display and search tables  

---

## 🎯 Future Enhancements

- Live score integration using external APIs  
- Role-based authentication (Admin / User)  
- Interactive analytics dashboard (charts for runs, wickets, wins)  
- Deployment on cloud (Heroku / AWS)  

---

## 🏁 Conclusion

The IPL DBMS Dashboard provides a practical and user-friendly interface for managing sports data, combining the reliability of relational databases with the flexibility of a web application. It not only fulfills academic requirements but also demonstrates real-world database-driven web development.

---

## 👩‍💻 Authors

- **N S Shashidhar**  
- **Poorvika Nagaraj**  
- **Pranathi Prasad Srivatsa**  

Under the guidance of **Chethana H R, Assistant Professor, RNSIT**  
