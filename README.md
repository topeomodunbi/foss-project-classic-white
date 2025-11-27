# **QueueMate Documentation**

## **Project Overview**

The **Campus Queue System** is a web-based platform that allows students to join service queues remotely and track their position in real time. It helps eliminate long physical queues across campus units such as ICT centers, administrative departments, and registration offices.

---

## **Key Features**

* Student Queue Registration
* Real-Time Queue Updates
* Optional Turn Notifications
* Admin Dashboard for Managing Queues
* User Authentication
* Responsive and User-Friendly Interface

---

## **System Architecture**

The system follows a **client–server architecture**.

* **Frontend:** React.js, CSS
* **Backend:** Express.js
* **Database:** MongoDB

---

## **Tools and Technologies Used**

* React.js
* CSS
* Express.js
* MongoDB
* Git & GitHub
* Postman

---

## **Project Structure**

```
foss-project-classic-white/
├─ backend/
│  ├─ middleware/
│  │  └─ authMiddleware.js
│  ├─ models/
│  │  ├─ Queue.js
│  │  └─ User.js
│  ├─ routes/
│  │  ├─ auth.js
│  │  ├─ queues.js
│  │  ├─ services.js
│  │  └─ userRoutes.js
│  ├─ node_modules/
│  ├─ .env
│  ├─ createAdmin.js
│  ├─ package-lock.json
│  ├─ package.json
│  └─ server.js
├─ frontend/
│  ├─ node_modules/
│  ├─ public/
│  └─ src/
│     ├─ components/
│     │  ├─ Navbar.js
│     │  ├─ QueueCard.js
│     │  └─ ServiceCard.js
│     ├─ pages/
│     │  ├─ Admin.js
│     │  ├─ Dashboard.js
│     │  ├─ Home.css
│     │  ├─ Home.js
│     │  ├─ Login.js
│     │  ├─ Queue.js
│     │  └─ Register.js
│     ├─ services/
│     │  └─ api.js
│     ├─ App.css
│     ├─ App.js
│     ├─ App.test.js
│     ├─ index.css
│     ├─ index.js
│     ├─ logo.svg
│     ├─ reportWebVitals.js
│     └─ setupTests.js
├─ .gitignore
└─ README.md
```

---

## **Installation**

### 1. Clone the repository

```bash
git clone https://github.com/<your-team>/<repo-name>.git
```

### 2. Navigate into the project directory

```bash
cd <repo-name>
```

### 3. Install dependencies

#### Client

```bash
cd client
npm install
```

#### Server

```bash
cd server
npm install
```

### 4. Start the development servers

#### Client

```bash
npm start
```

#### Server

```bash
npm run dev
```

---

## **Usage Guide**

### **For Students**

* Create an account or log in
* View available queues
* Join a queue
* Track your current position

### **For Admins**

* Log in to the admin dashboard
* Create and manage service queues
* Monitor queue status

---

## **Contribution Workflow (GitHub Collaboration)**

### **Branching Strategy**

* **main** – Production-ready code
* **dev** – Development integration branch
* **feature/<name>** – Individual feature branches

### **Workflow**

1. Create a feature branch
2. Implement your assigned task
3. Commit with meaningful messages
4. Open a Pull Request (PR)
5. Team review and approval
6. Merge into **dev**
7. Merge **dev** into **main** after testing

---

## **Team Roles and Contributions**

### **Frontend Development**

* **enasemmy (Emmanuel Enaohwo):** Navbar functionality
* **Esther Oluyemi:** Admin & Dashboard pages
* **witvhdoctor (Dike Ugonna):** Home page & styling
* **Olasubomi Omoloju:** Login & Queue pages
* **IniabasiDomingo:** Register page & API
* **Daveamhs16 (David Ahmed):** App.js setup

### **Backend Development**

* **Tope Omodunbi:** User & Queue models, auth middleware, Node setup
* **Enyiora Ifeanyi:** Authentication, queue & service routes
* **KEZ-collab (Ebere Zidane):** Admin account & packages
* **Tobiloba Adebayo:** Server file


---

## **Testing**

* Manual testing of user flows
* Postman used for API validation
* Authentication, queue creation, and queue updates tested
* Browser compatibility checks performed

---

## **Challenges and Solutions**

### **Challenges**

* Ensuring frontend & backend API consistency
* Environment setup issues among team members

### **Solutions**

* Frequent team sync-up meetings
* Debugging using Postman and console logs

---

## **Future Improvements**

* Add SMS or email notifications
* Integrate queue analytics
* Implement WebSocket-based real-time updates
* Build a mobile app
* Improve accessibility features

---

## **Acknowledgements**

* Open-source libraries & tools
* GitHub community
* Lecturer & team members

---

# **License (MIT License)**

```
MIT License

Copyright (c) 2025 Classic White

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
