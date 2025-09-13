# 🔐 Java Servlet Login & Registration System

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Servlets](https://img.shields.io/badge/Java_Servlets-4FC08D?style=for-the-badge&logo=java&logoColor=white)
![Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

A professional web application demonstrating secure user authentication using Java Servlets

</div>

## ✨ Features

- 🔐 **Secure User Authentication** - Login with session management
- 👥 **User Registration** - Create new accounts with validation
- 📱 **Responsive Design** - Clean, modern UI
- ⚡ **Servlet-Based** - Pure Java Servlet implementation
- 🔒 **Session Management** - Secure user sessions with timeout
- ✅ **Form Validation** - Client and server-side validation

## 🏗️ Project Structure

```
LoginProject1/
├── src/
│   └── main/
│       ├── java/                 # Servlet classes
│       └── webapp/
│           ├── index.html        # Landing page
│           ├── login.html        # Login form
│           ├── reg.html          # Registration form
│           └── WEB-INF/
│               ├── web.xml       # Deployment descriptor
│               └── lib/          # Dependencies
└── README.md
```

## 🖼️ Screenshots

### Home Page
![Home Page](https://raw.githubusercontent.com/Soumyadip012/Login_Project_Servlet/main/Screenshot%202025-09-14%20012438.png)
*Welcome page with navigation options*

### Registration Form
![Registration Form](https://raw.githubusercontent.com/Soumyadip012/Login_Project_Servlet/main/Screenshot%202025-09-14%20012302.png)
*User registration form with input fields*

### Login Form
![Login Form](https://raw.githubusercontent.com/Soumyadip012/Login_Project_Servlet/main/Screenshot%202025-09-14%20012348.png)
*Clean and intuitive login interface*

### Success Message
![Success Message](https://raw.githubusercontent.com/Soumyadip012/Login_Project_Servlet/main/Screenshot%202025-09-14%20012423.png)
*Registration confirmation page*

## 🚀 Quick Start

### Prerequisites

- ☕ Java JDK 11 or higher
- 🐈 Apache Tomcat 10.x
- ⚡ Eclipse IDE (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Soumyadip012/Login_Project_Servlet.git
   cd Login_Project_Servlet/LoginProject1
   ```

2. **Import into Eclipse** (Optional)
   - Open Eclipse → File → Import → Existing Projects into Workspace
   - Select the project folder

3. **Configure Tomcat Server**
   - Download [Apache Tomcat 10](https://tomcat.apache.org/download-10.cgi)
   - Add Tomcat server to Eclipse via Servers view

4. **Deploy and Run**
   - Right-click project → Run As → Run on Server
   - Access at: `http://localhost:8080/LoginProject1/`

## 📖 Usage

1. **Registration**: Navigate to register and create a new account
2. **Login**: Use credentials to access secure area
3. **Session Management**: Secure session maintenance
4. **Automatic Logout**: Session timeout for security

## 🛠️ Technology Stack

- **Backend**: Java Servlets, JSP
- **Frontend**: HTML, CSS, JavaScript
- **Server**: Apache Tomcat 10
- **Development**: Eclipse IDE

## 🔧 Configuration

- **web.xml**: Deployment descriptor for servlet mapping
- **Session Timeout**: Configurable in web.xml
- **Security**: Form-based authentication

## 🔮 Future Enhancements

- [ ] 🗄️ Database integration (MySQL/PostgreSQL)
- [ ] 🔐 Password encryption (BCrypt)
- [ ] 📧 Email verification
- [ ] 🔄 Password recovery
- [ ] 👥 Role-based access control
- [ ] 🎨 Bootstrap UI improvements
- [ ] 🌐 REST API endpoints
- [ ] 🐳 Docker containerization

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/Soumyadip012/Login_Project_Servlet/issues).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Soumyadip Kundu**

- 🌐 [GitHub Profile](https://github.com/Soumyadip012)
- 📧 [soumyadip012@gmail.com](mailto:soumyadip012@gmail.com)
- 💼 [LinkedIn](https://linkedin.com/in/soumyadip-kundu)

## 🙏 Acknowledgments

- Java Servlet API documentation
- Apache Tomcat team
- Eclipse Foundation

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>

---

*Note: This is a demonstration project for educational purposes. Always implement additional security measures for production applications.*
