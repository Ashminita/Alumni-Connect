# 🎓 Alumni Connect

Alumni Connect is a full-stack web application designed to bridge the gap between alumni and current students. It enables networking, event participation, job opportunities, and achievement sharing — all in one platform.

---

## 📌 Features

- 🔐 **User Authentication**: Secure login and registration for alumni and students.
- 🏠 **Home Page**: Clean landing page with easy navigation.
- 📅 **Events**: View upcoming college and alumni-hosted events (with Zoom integration).
- 🤝 **Alumni Connect**: Network and message between alumni and students.
- 💼 **Recruitment**: Alumni can post job opportunities; students can apply directly.
- 🏆 **Achievements**: Showcase individual or institutional accomplishments.
- 📰 **Announcements**: View latest updates from the college.

---

## 🛠️ Tech Stack

**Frontend**:  
- ReactJS  
- HTML5, CSS3  
- JavaScript  

**Backend**:  
- Node.js  
- Express.js  
- MongoDB  

**Other Tools & Integrations**:  
- Zoom API (for events)  
- Postman (for API testing)  
- Git & GitHub (for collaboration)

---

## 🧑‍💻 Contributors

- **Rajbir Deb Mishra**  
  Developed the **Home Page** with user **login/register functionality**, built the **Alumni Connect page**, and implemented the **Events section** with **Zoom integration** for seamless virtual event management.

- **Manaswini Mohapatra**  
  Designed and implemented the **Announcement page for Admin**, allowing college administrators to post official updates and important notices visible to all users.

- **Ashminita Baliarsingh**  
  Created the **Dashboard (second Home Page) after login** with role-based access, built the **Recruitment page** enabling alumni to post job opportunities and students to apply, and developed the **Achievements section** for showcasing user and institutional accomplishments.

---

## 📦 How to Run Locally

### 1. **Clone the repo**
   ```bash
   git clone https://github.com/Ashminita/Alumni-Connect.git
   cd Alumni-Connect
  ```
### 2.Install frontend dependencies

```bash
cd Frontend
npm install
```
### 3.Install backend dependencies

```bash
cd backend server
npm install
```
Setup environment variables
Create a .env file in the server directory and add:

```ini
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```
Run the application

```bash
# Start backend
cd backend server
npm start

# In a new terminal, start frontend
cd Frontend
npm run dev
```


