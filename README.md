# 🎓 FYP-Gate — Final Year Project Management System

**FYP-Gate** is a web-based platform developed using **Laravel**, **Bootstrap**, and **XAMPP**, created to simplify and automate the management of **Final Year Project (FYP)** activities.  
It streamlines processes such as project proposal submission, student-supervisor selection, quota management, and appointment scheduling.

---

## 🚀 Key Features
- 📄 **Project Proposal Submission:** Students can submit and manage FYP proposals online.  
- 👨‍🏫 **Supervisor Selection:** Enables supervisor-student pairing with automated quota enforcement.  
- 🧮 **Quota Management:** Supervisors can oversee and manage their student load effectively.  
- 🗓️ **Appointment Scheduling:** Allows easy meeting and consultation booking between students and supervisors.  
- ⚙️ **Admin Dashboard:** Centralized system control for managing users, projects, and allocations.  
- 📱 **Responsive Design:** Powered by **Bootstrap** for seamless access across devices.

---

## 🧰 Technologies Used
- **Framework:** Laravel (PHP)  
- **Frontend:** Bootstrap, Blade Templates  
- **Server Environment:** XAMPP (Apache, MySQL, PHP)  
- **Database:** MySQL  
- **Version Control:** Git & GitHub  

---

## ⚙️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/IbrahimBakour/Fyp-Gate.git

# Install dependencies
composer install
npm install

# Create .env file and configure database connection
cp .env.example .env

# Generate app key
php artisan key:generate

# Run migrations
php artisan migrate

# Start local server
php artisan serve
