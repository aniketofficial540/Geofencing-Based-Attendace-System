## 📍 Geofencing Attendance System

An automated attendance system that uses **geolocation verification** to mark student or employee presence based on their physical location. This project ensures that only users within a predefined **geofenced area** (like a campus or office) can successfully mark their attendance.

---

### 🚀 Features

* 📍 **Real-time location detection**
* ✅ **Automatic attendance marking** within a defined geofence
* 🔒 **Security layer** to prevent spoofing or location tampering
* 🧞 **Attendance logs** maintained with timestamp and user info
* 🗃️ **Admin dashboard** to view and export attendance reports

---

### 🧠 Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MySQL
* **Geolocation API:** HTML5 Geolocation

---

### 🧪 How It Works

1. The user opens the attendance portal on their mobile or laptop.
2. The app fetches the current **latitude and longitude** using the Geolocation API.
3. The server checks if the user is within the **predefined radius** using the **Haversine formula**.
4. If yes, attendance is marked and stored in the MySQL database with a timestamp.

---

### 📌 Use Cases

* College campuses with restricted zones
* Office spaces for employee attendance
* Events where physical presence verification is required
* Smart classroom systems

---

### 🔐 Security Considerations

* Data stored securely in a MySQL database

---

### 👨‍💼 Author

**Aniket Adarsh, Aditya Sharma, Subhash Sharma, Sahil K Gupta**
📍 Dehradun, India
✉️ [aniketofficial540@gmail.com](mailto:aniketofficial540@gmail.com)

---

