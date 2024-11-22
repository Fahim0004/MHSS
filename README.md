<p align="center">
  <img src="HSTU_Logo.png" alt="HSTU Logo" width="250" height="300">
</p>

<h3 align="center">
  Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200.
</h3>
<h3 align="center">
<b></b>Project Name: Mental Health Support System<b></b>
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>

<h3 align="center">
  Course Code: CSE 305
</h3>
<br>
<h1 align="center">Submitted By</h1>

 <p align="center">Fahim Hossain Dipo<br>Student ID: 2102004<br>Level: 3 Semester: I<br>Department of Computer Science and Engineering</p>
 <br>

<h1 align="center">Submitted To</h1>

 <p align="center">Pankaj Bhowmik<br>Lecturer<br>Department of Computer Science and Engineering</p>


<br><br><br>

# **Mental Health Support System**

## 📖 Overview
The **Mental Health Support System** aims to help students track their emotional state and engage in self-care activities. It provides a safe, private platform for logging moods, journaling thoughts, and accessing mental health resources. The project uses the **Software Development Life Cycle (SDLC)** to ensure systematic and high-quality development.

---

## 📝 Table of Contents
1. [Introduction](#introduction)  
2. [Technologies Used](#technologies-used)  
3. [SDLC Phases](#sdlc-phases)  
   - [Planning](#planning)  
   - [Requirements Gathering & Analysis](#requirements-gathering--analysis)  
   - [Design](#design)  
   - [Development](#development)  
   - [Testing](#testing)  
   - [Deployment](#deployment)  
   - [Maintenance](#maintenance)  
4. [Challenges and Solutions](#challenges-and-solutions)  
5. [Conclusion](#conclusion)  

---

## **Introduction**
The **Mental Health Support System** is a Java-based application designed to promote emotional well-being among students. It helps users track their moods, write journal entries, and gain insights into emotional patterns. This application is built with privacy, ease of use, and scalability in mind.

---

## **Technologies Used**
- **Frontend**: JavaFX  
- **Backend**: Java with REST APIs  
- **Database**: SQLite  

---

## **SDLC Phases**

### **1. Planning**
- **Objective**: Develop a platform to support students in tracking their emotional well-being, encouraging self-reflection, and providing helpful resources.  
- **Scope**:  
  - Log daily moods with notes.  
  - Write journal entries for reflection.  
  - Track gratitude to promote positivity.  
  - Analyze mood trends with visual insights.  
  - Provide mental health tips and resources.  
- **Risks**:  
  - Data privacy concerns.  
  - Ensuring consistent user engagement.  
  - Scalability to handle increasing user data.  

---

### **2. Requirements Gathering & Analysis**
- **Functional Requirements**:  
  - User registration and login.  
  - Mood logging with optional notes.  
  - Journaling for emotional reflection.  
  - Gratitude tracker for positivity.  
  - Notifications to encourage daily usage.  
  - Analytics for mood trend visualization.  

- **Non-Functional Requirements**:  
  - Data encryption to ensure privacy.  
  - Fast-loading, responsive design.  
  - Scalability to accommodate growing users.  

- **Tools & Technologies**:  
  - **Backend**: Java (using frameworks like Spring Boot).  
  - **Frontend**: JavaFX.  
  - **Database**: SQLite.  

---

### **3. Design**
- **System Architecture**:  
  - **Frontend**: User-friendly GUI built with JavaFX.  
  - **Backend**: REST APIs in Java for business logic.  
  - **Database**: SQLite for secure and efficient data storage.  

- **Database Schema**:  
  - **Users**: UserID, Username, Password, Email  
  - **Moods**: MoodID, UserID, Date, MoodType, Notes  
  - **Journals**: JournalID, UserID, Date, Entry  
  - **Gratitude**: GratitudeID, UserID, Date, Item  

- **UI/UX Design**:  
  - Wireframes for intuitive navigation.  
  - Responsive design for desktops.  

---

### **4. Development**
- **Frontend Development**:  
  - Build mood tracker and journaling screens using JavaFX.  
  - Add reusable components for analytics and gratitude tracking.  

- **Backend Development**:  
  - Develop APIs for user authentication and data management.  
  - Implement notifications for reminders.  

- **Version Control**:  
  - Use Git for source code management.  
  - Maintain structured branches for CI/CD.  

---

### **5. Testing**
- **Unit Testing**: Validate individual features like mood logging and journaling.  
- **Integration Testing**: Ensure seamless interaction between frontend and backend.  
- **User Acceptance Testing (UAT)**: Gather feedback from students.  
- **Security Testing**: Verify data encryption and system access.  
- **Performance Testing**: Test the app’s scalability and responsiveness.  

---

### **6. Deployment**
- **Staging Deployment**:  
  - Create a staging environment to simulate real-world usage.  
- **Production Deployment**:  
  - Deploy the system on cloud servers (e.g., AWS).  

---

### **7. Maintenance**
- Regular updates to add new features based on user feedback.  
- Routine performance monitoring and security testing.  
- Periodic backups of all user data.  

---

## **Challenges and Solutions**

### **Challenge 1: Ensuring Data Privacy**  
- **Problem**: Sensitive user data requires robust security to avoid breaches.  
- **Solution**: Implement end-to-end encryption (AES for data, TLS for communication) and adopt secure coding practices. Regularly conduct security audits.  

### **Challenge 2: Encouraging Consistent Use**  
- **Problem**: Users may forget to use the system regularly.  
- **Solution**: Add notifications, gamify the experience (e.g., streaks), and include engaging analytics to show meaningful trends.  

---

## **Conclusion**
The **Mental Health Support System** offers students a platform to reflect, grow, and take charge of their mental well-being. By leveraging SDLC principles, this project ensures high-quality, user-focused development. It fosters self-awareness and mental health positivity, contributing to a better and more mindful student community.  

---
