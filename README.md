# ATTENDINSIGHTS

**🎓 AttendInsights — AI-Powered Student Attendance Monitoring System**

**📌 Overview**

AttendInsights is a smart attendance monitoring platform designed to modernize student attendance management through AI insights, automation, role-based dashboards, and scalable deployment.


**Built using:**
HTML / CSS / JavaScript
Power Apps
Power Automate
PCF (PowerApps Component Framework)
Excel / API Data Sources

**This system provides:**
Dynamic Student Login
Admin Login
Personalized Student Dashboard
Institutional Admin Dashboard
Attendance Alerts
AI-driven attendance analysis
Future-ready API integration


🚀 **Key Features**
👨‍🎓 **Student Module**
Authentication
Student login via Roll Number
Default password validation (Thub@123)
Redirects to personalized student.html
Dashboard
Attendance %
Present Days
Absent Days
Session Count
Attendance Status
Alerts
AI recommendations

**🛡️ Admin Module**
Authentication
Admin login via Faculty/Admin ID
Default admin credentials (admin / Admin@123)
Redirects to admin.html
Dashboard
Total Students
Average Attendance
At-Risk Students
Excellent Students
Sessions
Alerts Sent
Analytics-ready architecture

**🤖 Automation Features**

**Using Power Automate:**
Attendance below 75% → Warning Email
3-Day continuous absence → Parent Alert
5-Day continuous absence → Escalated Warning
Excellent attendance → Appreciation Notification

**🧠 AI Integration**
Attendance health scoring
Predictive warning system
Personalized insights
Admin trend monitoring
Future chatbot integration


**🗂️ Project Structure**
AttendInsights/
│
├── login.html              # Main Login Page
├── student.html            # Student Dashboard
├── admin.html              # Admin Dashboard
│
├── css/
│   └── styles.css
│
├── js/
│   └── login.js
│
├── Backend/
│   ├── Backend.py
│  
│
├── dataset/
│   └── AttendanceData.xlsx
│
└── README.md


**🔐 Default Credentials**
**Student:**
Password: Thub@123
**Admin:**
Username: admin
Password: Admin@123

**📊 Dataset Requirements**
**Current table:**
AttendanceData

**Required columns:**
roll_no
sessions
attended
percentage

**🌐 Login Flow**
**Student:**
Student Toggle → Roll Number + Password → student.html
**Admin:**
Admin Toggle → Admin ID + Password → admin.html

**⚙️ PCF Deployment Commands**
**Build:**
npm run build
**Deploy:**
pac pcf push --publisher-prefix th

**🎨 UI Design Philosophy**
Green institutional branding
Split-screen login
Dynamic role switching
Responsive dashboard architecture
Scalable enterprise interface

**📈 Future Roadmap**
**Phase 1:**
Static login
Student dashboard
Admin dashboard
**Phase 2:**
Power Apps integration
Excel dataset binding
Dynamic dashboards
**Phase 3:**
API integration
Live attendance sync
**Phase 4:**
AI predictions
Parent dashboard
Power BI analytics
Mobile deployment


**🛠️ Tech Stack**
**Frontend:**
HTML5
CSS3
JavaScript
Microsoft Ecosystem:
Power Apps
Power Automate
Power Platform CLI
PCF
**Data:**
Excel Tables
SharePoint
REST APIs (future)

Backend
For Backend We have used the Power Automate for AI the code we build is Backend.py file 

**🎯 Objectives**
Automate attendance management
Reduce manual tracking
Improve student accountability
Deliver actionable insights
Enhance academic intervention
Enable enterprise scalability

**📷 Screens Included**
Login Page
Student Dashboard
Admin Dashboard

**👨‍💻 Author**
Developed as an academic + enterprise-grade smart attendance platform integrating:
Microsoft Power Platform
Automation
AI Concepts
