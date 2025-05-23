# 🔗 Shorti.fy - URL Shortener (🚀 In Progress) | ✨ Custom Links, ⏳ Expiration & 🔒 Security

## 📝 Overview
Shorti.fy is a web application that allows users to convert long URLs into short, shareable links. It offers additional features like custom short URLs, expiration dates, click tracking, detailed visitor tracking (such as masked IP addresses, location, and device information), QR code generation, and password protection for private links. This allows users to add an extra layer of security to their shortened URLs by requiring a password before anyone can access them.


---


## 🚀 Features  

### 🔑 Authentication  
- **Sign In & Sign Up:** Secure authentication for users.
- **Google OAuth2 Login:** Users can sign in with their Google account for a seamless experience.
- **Forgot Password:** Reset password functionality for account recovery.

### 🔗 URL Shortening  
- **Convert Long URLs to Short URLs:**  
  - Enter a long URL (e.g., https://www.verylongwebsite.com/articles/how-to-build-a-url-shortener-in-java).  
  - The system generates a short link (e.g., s-fy.onrender.com/Xz4).  

- **Expiration Dates:**  
  - Users can set expiration dates for short links.  
  - Expired links become inactive.  

### ✏️ URL Management  
- **Edit Shortened URLs:** Users can update the original long URL.  
- **Delete URLs:** Users can remove their shortened links from the system.  


### 🔒 Password-Protected Short URLs
- **Secure Your Links:** Users can choose to set a password when creating a short URL.
- **Access Control:** Anyone trying to access the link will be prompted for the password.
- **Password Validation:** Only users who enter the correct password will be redirected to the original URL.
- **Enhanced Privacy:** Protect sensitive links with an extra layer of security.


### 📊 Click Tracking & Analytics  
- **Track link clicks:** View how many times a short link has been accessed.  
- **Other tracking:** Capture details like partially masked IP, device, and location.  

### 📌 QR Code Generation
- **Auto-generated QR Codes:** Every shortened URL automatically gets a QR code.  
- **Downloadable QR Codes:** Users can download QR codes as images for easy sharing.  


---


## 🖥️ Pages

### 🔓 Public Pages
- Sign In
- Sign Up
- Forgot Password

### 🔒 Authenticated Pages
- **Home:** The main page for shortening URLs. Users can enter a long URL and generate a short link.
- **Dashboard:** Displays analytics, including graphs and statistics on link usage.
- **My URLs:** Manage all created short links—view full details, edit, or delete URLs.


---


### 🛠 Technologies Used

#### 💻 Frontend (Angular + Tailwind CSS)
  - Interactive UI for URL management, authentication, and tracking.
  - Responsive design for seamless cross-device experience.

#### 🔧 Backend (Spring Boot)
  - Secure authentication, URL shortening, and link expiration.
  - User management, password recovery, and analytics tracking.

#### 📦 Database (PostgreSQL)
  - Stores URL mappings, expiration times, and user data.

#### 🛢️ Testing Database (H2)
  - In-memory database for testing and development.
  - Speeds up testing without affecting the main database.

#### ⚡ Caching (Caffeine Cache)
  - Enhances performance by storing frequently accessed URLs in memory.
  - Reduces database load and speeds up redirections.


---



## 🌍 Live
- 🔗 **Shorti.fy:** [https://s-fy.netlify.app/](https://s-fy.netlify.app)


---


## 📂 Repositories
- **Frontend Repository:** [GitHub - Shorti.fy Frontend Repository](https://github.com/JonArbell/shorti.fy-frontend)  
- **Backend Repository:** [GitHub - Shorti.fy Backend Repository](https://github.com/JonArbell/shorti.fy-backend)  


---

👨‍💻 Developed & maintained by *Jon Arbell De Ocampo*
