# Ethnotech_Mini_Projects_March
# 📍 Location-Based Service App

## 👩‍💻 Author

**Lourdu Monisha**

---

## 📖 Overview

The **Location-Based Service App** is a desktop application developed using Java Swing and MongoDB.
It allows users to register, log in, and explore places based on a given location. Users can also add new places to the system.

This project demonstrates full-stack development concepts including UI design, database integration, and user authentication.

---

## 🚀 Features

* 🔐 User Registration & Login System
* 📍 Search Places by Location
* ➕ Add New Places (Hospitals, Restaurants, Bus Stops, etc.)
* 🗄️ MongoDB Database Integration
* 🖥️ Interactive GUI using Java Swing

---

## 🛠️ Tech Stack

| Technology     | Description               |
| -------------- | ------------------------- |
| Java           | Core programming language |
| Swing          | GUI (User Interface)      |
| MongoDB        | NoSQL Database            |
| MongoDB Driver | Java connectivity         |

---

## 📂 Project Structure

```
LocationBasedApp/
│── src/
│   ├── Main.java
│   ├── DBConnection.java
│   ├── AuthService.java
│   ├── LocationService.java
│   ├── ui/
│   │   ├── LoginUI.java
│   │   ├── RegisterUI.java
│   │   ├── DashboardUI.java
│   │   ├── AddPlaceUI.java
│   ├── model/
│   │   ├── User.java
│   │   ├── Place.java
│
│── lib/
│   ├── mongodb-driver-sync.jar
│   ├── bson.jar
│   ├── mongodb-driver-core.jar
│
│── resources/
│   └── config.properties
│
│── README.md
│── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Prerequisites

* Install Java (JDK 8 or above)
* Install MongoDB and start the server
* Download MongoDB Java Driver

---

### 2️⃣ Database Setup

Create a database and collections:

* Database: `locationDB`
* Collections:

  * `users`
  * `places`

---

### 3️⃣ Run the Application

1. Open project in IDE (Eclipse / IntelliJ)
2. Add MongoDB driver JARs to classpath
3. Run:

```
Main.java
```

---

## 🔐 Authentication Flow

* New users can register
* Existing users can log in
* Credentials are validated using MongoDB

---

## 📍 Functional Flow

1. User logs into the system
2. Enters a location
3. System fetches places from database
4. Displays results in UI
5. User can add new places

---


---

## 🔮 Future Enhancements

* 🗺️ Google Maps API Integration
* 🔐 Password Encryption (BCrypt)
* 🌐 Web version using Spring Boot
* 📱 Mobile version (Android)

---

## 📌 Conclusion

This project is a practical implementation of a location-based service system using Java technologies.
It showcases database connectivity, GUI development, and authentication mechanisms.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
