# 🍲 FoodFusion – Community Recipe Sharing Platform

FoodFusion is a dynamic PHP and MySQL-based web platform that allows users to share, discover, and interact with recipes. It includes features such as user registration, community cookbook submissions, resource downloads, and a contact form – all designed to create an engaging culinary experience.

## 📌 Project Description

The goal of this project is to provide a platform where food lovers can:
- Join a community
- Submit their own recipes
- Download culinary resources (PDFs and videos)
- Interact with other users in a shared cookbook space

It was developed as part of the NCC Education Level 5 Back-End Web Development module.

---

## 🧱 Features

- ✅ Responsive homepage and navigation bar  
- ✅ "Join Us" form with input validation  
- ✅ Recipe display by category  
- ✅ Community Cookbook: post and interact with user-submitted recipes  
- ✅ User registration, login, and password reset system  
- ✅ Secure user authentication and data storage  
- ✅ Downloadable culinary resources (recipe cards and tutorial videos)  
- ✅ Contact form with backend data handling

---

## 💻 Technologies Used

- **HTML & CSS**  
- **PHP**  
- **MySQL**  
- **WAMP Server** (for local development)  
- **JavaScript (basic)**  
- **GitHub** (for version control)

---

## 🚀 Deployment

The project can be deployed using:
- **WAMP/XAMPP** locally
- Or cloud-based services like **000webhost**, **InfinityFree**, or **cPanel hosting** with MySQL support

---

## 🔐 Security Features

- Passwords are encrypted before storing in the database  
- Input validation for all forms to prevent SQL injection and invalid data  
- Login system includes lockout mechanism after multiple failed attempts

---

## 🧪 Testing

| Test Area            | Test Case Description                                         | Expected Outcome                                           | Actual Result | Issues Resolved                   |
|----------------------|---------------------------------------------------------------|------------------------------------------------------------|---------------|-----------------------------------|
| Homepage             | Verify navigation bar responsiveness                          | Navigation bar works correctly on all devices              | ✅             | —                                 |
| Join Us Form         | Validate and submit form                                      | Form validates inputs and submits successfully             | ✅             | —                                 |
| Community Cookbook   | Submit and view recipes                                       | Users can post recipes and view others                     | ✅             | Added file size limit validation  |
| Contact Us Form      | Submit message and handle backend                             | Message saved and feedback given to user                   | ✅             | Fixed missing field bug           |
| Resources            | Download PDF and video files                                  | Users can download resources without error                 | ✅             | Optimized file naming             |
| User Auth            | Register, login, reset password                               | All auth functions work securely and smoothly              | ✅             | Strengthened password policy      |
| Security             | Ensure data encryption and secure sessions                    | User data is encrypted and sessions are protected          | ✅             | Enabled HTTPS redirection         |

---

## ⚙️ Setup Instructions (Localhost)

1. Clone this repository or download the ZIP
2. Copy the project folder into your local `www` directory (e.g., `C:\wamp64\www\FoodFusion`)
3. Import the SQL database using **phpMyAdmin**
4. Update `config.php` or connection file with your database credentials
5. Run `http://localhost/FoodFusion/index.php` in your browser

---

## 📌 Project Highlights

- Learned to use version control (Git & GitHub)
- Practiced secure back-end development
- Built real-world forms and authentication systems
- Followed structured development and testing process

---

## 📄 License

This project is for **educational purposes only** as part of the NCC Level 5 Diploma in Computing.

---

## 🙋‍♂️ Author

**Jean-Daniel Sonou**  
Computer Science Student – IPMC College of Technology, Accra  
Future Data Scientist & Smart Farming Enthusiast  
