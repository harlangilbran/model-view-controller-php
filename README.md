## 🎓 Simple MVC PHP - CRUD for Student Data  

This is a simple web application built with **PHP (Object-Oriented Programming - OOP)** using the **Model-View-Controller (MVC)** pattern. This application enables **CRUD (Create, Read, Update, Delete)** operations for student data with a minimal interface styled using **Bootstrap**.

### ✨ Features  
✅ Separation of logic, data, and views using the **MVC** architecture  
✅ CRUD **(Create, Read, Update, Delete)** for student data  
✅ Responsive design using **Bootstrap** with no custom CSS  
✅ Clean and structured code with **PHP OOP**  

### 🔧 Technologies Used  
- **PHP (OOP - Object-Oriented Programming)**  
- **MySQL** for the database  
- **Bootstrap** for responsive styling  
- **Apache** or any local server  

### 📂 Folder Structure  
Below is the main folder structure:  
```
/app  
│── /config           # Application configuration files  
│── /controllers      # Handles application logic  
│── /core             # Core of the MVC framework (routing, database, etc.)  
│── /models           # Classes to manage data (Students, Users, etc.)  
│── /views            # Folder for web page templates  
│    ├── /templates   # Shared header and footer  
│── init.php          # Main initialization file  

/public               # Folder for public files (CSS, JS, images, etc.)
│── /css              # Bootstrap or other CSS files
│── /js               # JavaScript files  
│── /img              # Image files  

.htaccess             # Apache configuration for routing
index.php             # Main entry point for the application
```

### 🚀 How to Run  
1. **Clone the Repository**  
   Clone this repository to your local machine:  
   ```bash
   git clone https://github.com/username/repository.git
   cd repository
   ```

2. **Set Up the Database**  
   - Create a new database in MySQL  
   - Import the provided `mahasiswa.sql` file  
   - Ensure the database configuration in `/app/config/config.php` is correct  

3. **Run the Local Server**  
   Use the following command to start the server:  
   ```bash
   php -S localhost:8000
   ```

4. **Access the Application**  
   Open your browser and go to: **http://localhost:8000**

## 🖼️ Main Pages
The application includes the following pages:

Home: A landing page introducing the application.
Mahasiswa (Students): Displays a list of students with CRUD features (Add, Edit, Delete).
About: A page providing details about the application.
## 📜 License
This project is open-source and free to use or modify for further development. 🚀
## 📝 Note
This project is the result of my learning from materials I studied on YouTube. If there are similarities with other projects, it is purely due to shared reference sources, and I sincerely apologize for any unintentional resemblance. The main purpose of this project is to learn and enhance my skills in PHP and the MVC architecture.

## 🎓 Simple MVC PHP - CRUD Data Mahasiswa  

Proyek ini adalah aplikasi web sederhana berbasis **PHP (Object-Oriented Programming - OOP)** dengan pola **Model-View-Controller (MVC)**. Aplikasi ini digunakan untuk **CRUD (Create, Read, Update, Delete)** data mahasiswa dengan tampilan sederhana yang menggunakan **Bootstrap** sebagai framework CSS.

### ✨ Fitur  
✅ Pemisahan logika, data, dan tampilan menggunakan arsitektur **MVC**  
✅ CRUD **(Create, Read, Update, Delete)** untuk data mahasiswa  
✅ Desain responsif menggunakan **Bootstrap** tanpa CSS tambahan  
✅ Kode terstruktur dengan penerapan **PHP OOP**  

### 🔧 Teknologi yang Digunakan  
- **PHP (OOP - Object-Oriented Programming)**  
- **MySQL** sebagai database  
- **Bootstrap** untuk tampilan responsif  
- **Apache** atau server lokal lainnya  

### 📂 Struktur Folder  
Berikut adalah struktur folder utama:  
```
/app  
│── /config           # File konfigurasi aplikasi  
│── /controllers      # Mengatur logika aplikasi  
│── /core             # Inti dari framework MVC (routing, database, dll.)  
│── /models           # Kelas yang mengelola data (Mahasiswa, User, dll.)  
│── /views            # Folder untuk menampilkan halaman web  
│    ├── /templates   # Header dan footer bersama  
│── init.php          # Inisialisasi utama aplikasi  

/public               # Folder untuk file publik (CSS, JS, gambar, dll.)
│── /css              # Bootstrap atau file CSS lainnya
│── /js               # File JavaScript  
│── /img              # File gambar  

.htaccess             # Konfigurasi Apache untuk routing
index.php             # Entry point utama aplikasi
```

### 🚀 Cara Menjalankan  
1. **Clone Repository**  
   Clone repository ini ke komputer lokal:  
   ```bash
   git clone https://github.com/username/repository.git
   cd repository
   ```

2. **Setup Database**  
   - Buat database baru di MySQL  
   - Import file `mahasiswa.sql` yang disediakan  
   - Pastikan konfigurasi database di `/app/config/config.php` sudah sesuai  

3. **Jalankan Server Lokal**  
   Gunakan perintah berikut untuk menjalankan server:  
   ```bash
   php -S localhost:8000
   ```

4. **Akses Aplikasi**  
   Buka browser dan akses: **http://localhost:8000**

## 🖼️ Tampilan Utama  
Aplikasi memiliki halaman:  
- **Home**: Halaman utama  
- **Mahasiswa**: Menampilkan daftar mahasiswa dan fitur CRUD  
- **About**: Informasi tentang aplikasi  

## 📜 Lisensi  
Proyek ini bersifat open-source dan bebas digunakan untuk pengembangan lebih lanjut. 🚀  

## 📝 Catatan
Proyek ini adalah hasil pembelajaran saya dari materi yang saya pelajari di YouTube. Jika terdapat kesamaan dengan proyek lain, itu murni karena kesamaan sumber referensi, dan saya memohon maaf atas ketidaksengajaan tersebut. Tujuan utama dari proyek ini adalah untuk belajar dan mengembangkan kemampuan saya dalam PHP dan arsitektur MVC.


