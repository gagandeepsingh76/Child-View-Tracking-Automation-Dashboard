# 👶 Child Tracking System (Android)

The **Child Monitoring System** is an Android-based software application that allows parents to monitor their child's mobile phone activity. The system collects important information such as call details, SMS events, alerts, and location updates, and stores them on a centralized server or cloud database.

Parents can monitor where their child is located using **GPS tracking**, where the latitude and longitude values are periodically updated in the database. The system helps in developing an efficient **geographical asset tracking solution** while conserving valuable mobile resources by dynamically adapting the tracking scheme using context-aware techniques.

Alerts such as incoming calls, text messages, multimedia messages, and location updates are stored on the centralized server. Parents can later log in to the system and view their child’s mobile usage and activity details.

---

# 📌 Project Overview

This project focuses on creating a **mobile monitoring and tracking system** that allows parents to stay informed about their child’s device activity and location.

The system performs the following tasks:

- Monitors incoming and outgoing calls
- Tracks SMS related events
- Records alerts and phone activity
- Tracks real-time GPS location
- Uploads location coordinates to a server
- Runs background services for continuous monitoring

---

# 🎯 Objective

The objective of the Child Monitoring System is to:

- Provide parents with a way to monitor child mobile usage
- Track the geographical location of the child
- Store monitored data on a centralized server
- Provide alerts and logs for calls and messages
- Optimize mobile resources while performing background tracking

---

# ✨ Key Features

- 📞 Call activity monitoring
- 💬 SMS event monitoring
- 📍 GPS location tracking
- ☁️ Cloud database storage
- 🔔 Alert monitoring system
- ⚙️ Background monitoring service
- 📱 Boot event detection
- 📡 Phone state monitoring

---

# 🛠️ Technologies Used

- Java
- Android SDK
- Broadcast Receivers
- Background Services
- GPS / Location Services
- Cloud / Server Database

---

# 📂 Project Structure

```text
Child-Tracking-System-Android
│
├── child
│   │
│   ├── dao
│   │   ├── ConnectionManager.java
│   │   └── UpdateDB.java
│   │
│   ├── protect
│   │   └── ParameterServlet.java
│   │
│   ├── common
│   │   ├── SharedMethods.java
│   │   └── SharedValues.java
│   │
│   ├── receivers
│   │   ├── AlarmReceiver.java
│   │   ├── BootReceiver.java
│   │   ├── MyPhoneStateListener.java
│   │   ├── OutCallReceiver.java
│   │   └── SmsReceiver.java
│   │
│   └── services
│       └── BackgroundService.java
│
├── src
│   ├── ConnectionManager.java
│   └── LoginChecker.java
│
├── util
│
├── CPS.java
│
└── README.md
```

---

# 📖 Package Description

### `child/dao`

Contains database related operations.

- **ConnectionManager.java** – Manages connection with database/server
- **UpdateDB.java** – Updates monitored data into database

### `child/protect`

Contains parameter processing logic.

- **ParameterServlet.java** – Handles parameter related operations

### `child/common`

Contains shared values and reusable methods.

- **SharedMethods.java**
- **SharedValues.java**

### `child/receivers`

Contains Android broadcast receivers for handling events.

- **AlarmReceiver.java** – Handles scheduled tasks
- **BootReceiver.java** – Starts services when device boots
- **MyPhoneStateListener.java** – Monitors phone state
- **OutCallReceiver.java** – Handles outgoing call events
- **SmsReceiver.java** – Monitors SMS messages

### `child/services`

Contains background services.

- **BackgroundService.java** – Runs monitoring services continuously in background

### `src`

Contains supporting classes.

- **ConnectionManager.java**
- **LoginChecker.java**

---

# ⚙️ How the System Works

1. The Android application runs monitoring services in the background.
2. Broadcast receivers listen for events such as calls, SMS, alarms, and boot completion.
3. The system collects GPS location coordinates.
4. Latitude and longitude values are periodically uploaded to the database.
5. Alerts and activity details are stored on a centralized server.
6. Parents can later log in and view the monitored information.

---

# 📍 Use Cases

This system can be useful for:

- Parent child safety monitoring
- Child location tracking
- Mobile activity monitoring
- Learning Android monitoring architecture
- Academic Android development projects

---

# ⚠️ Ethical Notice

This project is intended **only for educational and research purposes**. Monitoring systems should always be used responsibly and with proper consent according to privacy regulations.

---

# 🚀 Future Improvements

Possible improvements include:

- Real-time parent dashboard
- Push notification alerts
- Better cloud synchronization
- Enhanced UI for monitoring panel
- Improved security and encryption
- Battery optimized background tracking

---

# 🧰 Tech Stack

- Java
- Android SDK
- Broadcast Receivers
- Background Services
- GPS / Location Services
- Cloud Database Integration

### Hardware Support

✔ Android Mobile Device  
✔ GPS Enabled Device  
✔ Internet Connectivity  

---

# 👨‍💻 Author

**Gagandeep Singh**  
Computer Science Student  

Interested in:

- Android Development
- Java Programming
- Mobile Application Development
- GPS Tracking Systems
- Software Engineering

---

# ⭐ Support

If you find this repository useful, consider **starring the project** to support the work.

---

# 🏷 GitHub Topics

android  
java  
child-tracking-system  
gps-tracking  
mobile-monitoring  
android-services  
broadcast-receiver  
location-tracking  
cloud-database  
parental-monitoring  

---

# 📌 Conclusion

The **Child Monitoring System** provides a structured Android solution for monitoring a child's mobile activity and location through background services and event listeners. By combining GPS tracking, event monitoring, and cloud database storage, the system enables parents to stay informed about their child’s safety and mobile usage.
