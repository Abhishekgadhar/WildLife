# 🐾 WildLife Explorer – Wildlife Tour & Booking Management System

A dynamic J2EE-based web application that enables users to explore and book wildlife tour packages, safaris, accommodations, and guide services. Built using Java Servlets, JSP, JDBC, and MySQL, the platform includes admin functionality to manage and approve bookings. The system follows the MVC architecture with modular layers (DAO, DTO, Controller).

---

## 🚀 Features

- 🏞️ Browse wildlife tour packages and safari options
- 🛏️ Book accommodation and guide services
- 👤 User registration and login
- 📦 Package selection with detailed view
- 📝 Booking form with user details and preferred package
- 🔐 Admin login to manage bookings
- ✅ Admin approval or rejection of each user booking
- 📧 Contact form for inquiries
- 📱 Mobile-responsive design using Bootstrap

---

## 🛠️ Tools & Technologies Used

| Layer        | Technologies                                     |
|--------------|--------------------------------------------------|
| **Frontend** | HTML5, CSS3, Bootstrap, JSP                      |
| **Backend**  | Java, Servlets, JDBC                             |
| **Database** | MySQL                                            |
| **Architecture** | MVC (Model-View-Controller), DAO, DTO       |
| **Tools**    | Apache Tomcat Server, Eclipse/IntelliJ, Postman |

---

## 💡 How It Works (MVC Flow)

1. **User** fills a booking or contact form on a JSP page  
2. **Servlet** receives the data and creates a DTO object  
3. **DAO** interacts with the MySQL database via JDBC  
4. **Admin** views bookings and accepts or rejects them  
5. **Responses** are shown back to the user via JSP

