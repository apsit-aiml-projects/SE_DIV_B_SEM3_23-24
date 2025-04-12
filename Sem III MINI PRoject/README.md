# Event Website

This is a simple event registration website using HTML, CSS, PHP, and SQLite. The project includes registration, login, and event booking functionality.

## 📁 Project Structure

```
event website/
├── index.html              # Home page
├── Register.html           # Registration page
├── register2.php           # Registration form handler
├── login2.php              # Login page
├── login_process.php       # Login handler
├── book.html               # Event booking page
├── process_form.php        # Booking handler
├── connect.php             # Database connection
├── style.css               # Main styles
├── images/                 # Blog/gallery images
└── *.css                   # Other stylesheets
```

## 🛠️ How to Run This Project

### Option 1: Using XAMPP (Recommended for Beginners)

1. **Install XAMPP**  
   [Download XAMPP](https://www.apachefriends.org/index.html) and install it on your system.

2. **Start Apache Module**  
   Open the XAMPP Control Panel and start the **Apache** server.

3. **Move Project Folder**  
   Copy the extracted `event website` folder into this path:
   ```
   C:\xampp\htdocs\
   ```

4. **Rename the Folder (Optional)**  
   To avoid issues with spaces in URLs, rename the folder from `event website` to `event-website`.

5. **Run the Project**  
   Open your browser and go to:
   ```
   http://localhost/event-website/index.html
   ```

6. **You're Done!**  
   The site should be running locally. You can test registration, login, and booking features.

---

### Option 2: Using PHP's Built-in Server (Advanced)

If you have PHP installed locally:

```bash
cd path/to/event-website
php -S localhost:8000
```

Then open:
```
http://localhost:8000/index.html
```

---

## ⚠️ Notes

- Make sure PHP is enabled and supported in your server environment.
- This project assumes a working SQLite or PHP setup without a GUI admin panel.
- Check that the database file or logic inside `connect.php` works correctly if you plan to use SQLite.

## 📄 License

Free to use for learning and personal projects.
