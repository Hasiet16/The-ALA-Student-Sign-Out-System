
  # Student Sign-Out System

  This is a code bundle for the prototype of ALA's Student Sign-Out System. 
  # ClearForm

## Project Overview

**"ClearForm"** is a modern digital clearance form system designed for educational and corporate environments. It streamlines the process of requesting and granting clearances digitally, eliminating paper forms, manual approvals, and unnecessary delays. Users (Students of ALA) Return all the materials that were given by the school in the designated areas, and their status will be updated from the receptiption portal. Then, if they have met all the requirements, the student's status on their teacher's portal will change, and will be pending for approval. The webApp has different portals for all hall heads, year heads, and admin. While all the approvals are happening the students will also be able to see their status. Another feature in the teacher's portal is that when they first give out textbooks, calculators or any materials, they can register it so that when they are settiing the requirement for their approval, they can reference it.
 

---

## Key Advantages

**1. Fully Digital Workflow:**  
No paper, no manual signatures. Requests are submitted, tracked, and completed digitally.   

**2. Multi-Role Support:**  
Supports administrators, teachers, hall heads, year heads, and advisors with role-specific portals.  

**3. Lightweight and Modular:**  
Built with Node.js and Vite, allowing fast performance and easy feature expansion.  

**4. Notifications & Reminders:**  
Automatic email alerts and in-app notifications reduce delays and improve response times.  

**5. Audit-Ready Records:**  
All submissions, approvals, and comments are logged securely for auditing and reporting.  

---

## Demo Access

ClearForm is currently **hosted as a demo**, so no installation or local setup is required for general users.  

**Accessing the Demo:**  
1. Visit the demo URL: [https://alatotheworld.com/]
2. Use one of the demo accounts:  

| Role              | Username                                      
|-------------------|----------------------------------------------
| Student           | aayanlade24@alastudents.org                 
| Admin             | admin@africanleadershipacademy.org
|Reception Staff    | reception@africanleadershipacademy.org
|Teacher            | IAdeleke@africanleadershipacademy.org
|Hall Head          | brown@africanleadershipacademy.org
|Advisor            | CDelight@africanleadershipacademy.org
|Year Head          | SThulo@africanleadershipacademy.org
|Password           | password (for all accounts)

3. Explore the system: submit requests, approve/reject clearances, and check notifications.  


---

## System Architecture

**Conceptual Architecture Diagram**

**Core Components:**  
- **Frontend (Vite + React):** Clean and responsive form interface  
- **Backend (Node.js + Express):** Handles form submissions, approvals 
- **Database:** Stores all requests, user info, and approval history  

---

## Project Code Structure

ClearForm/
├── frontend/ # Vite + React frontend
│ ├── src/
│ │ ├── components/ # UI components
│ │ ├── pages/ # Page views
│ │ └── utils/ # Helper functions
│ └── index.html
├── backend/ # Node.js + Express backend
│ ├── controllers/ # API request handlers
│ ├── routes/ # API endpoints
│ ├── models/ # Database models
│ ├── services/ # Notifications & utilities
│ └── app.js # Entry point
├── database/ # Database schema / migration scripts
├── .env.example # Example environment configuration
├── package.json # Project dependencies
└── README.md

---
  
  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.

  ### Built by Ayanfeoluwa, Hassiet, and Yabets
  
