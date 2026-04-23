# Inn ‘n Out: A Digital Leave Pass Management System for Pisay Dormers

---

## 1. Project Statement / Rationale

Students living in dormitories, especially scholars, experience recurring difficulties in managing leave passes due to the current manual system. Every week, particularly during Fridays and Sundays, dormers are required to line up physically to submit their leave slips. This results in long queues, time pressure, and unnecessary stress, especially for students who are also managing heavy academic workloads.

The manual process also increases the chances of errors, such as illegible handwriting, misplaced records, and delays in approval. These inefficiencies affect both dormers and dorm staff. Dormers lose valuable time that could have been used for studying or resting, while dorm staff struggle to manage and organize large volumes of paper records.

Addressing this problem is important because it directly impacts students’ time management, productivity, and overall well-being. By improving the leave pass system, the project supports a more efficient dormitory process and a better student experience.

---

## 2. Project Overview and Relevance

The project, Inn ‘n Out, is a digital leave pass management system designed to replace the traditional manual process used by dormers. The system allows users to register, log in, submit leave requests, and track their status, while dorm staff can review, approve, or reject requests through a centralized platform.

This project is highly relevant to Python programming, database management, and data analysis concepts. The system is implemented using structured programming in C++, applying concepts such as file handling, data structures (vectors and structs), and input validation.

Although the current version uses text files as storage, it follows the logic of CRUD operations (Create, Read, Update, Delete), which are essential in database systems. The system also organizes and processes data such as user accounts and leave pass records, demonstrating basic data handling and analysis (e.g., counting approved, pending, and rejected requests).

Overall, the project reflects real-world applications of programming by solving an actual problem using computational methods.

---

## 3. Objectives

### General Objectives

To develop a digital system that processes dormers’ leave passes efficiently and reduces reliance on manual methods.

### Specific Objectives

- To allow dormers to submit leave passes digitally instead of lining up physically  
- To reduce the time required to process leave requests  
- To enable dorm staff to review and manage leave passes efficiently  
- To store leave pass records in an organized and accessible format  
- To implement status tracking for each leave request (Pending, Approved, Rejected)  
- To minimize human errors caused by manual record-keeping  
- To generate simple reports summarizing leave pass statuses  

---

## 4. Methodology / Technical Approach

The system was developed using C++ and follows a structured programming approach. It simulates a basic information system by integrating user interaction, data storage, and record management.

### 1. User Management System

The program allows users to register and log in with a username, password, and role (Dormer or Manager). This demonstrates authentication and role-based access, where different users are given different functionalities.

### 2. Data Storage (File Handling as Database Simulation)

Instead of using a full database system, the program uses text files (users.txt and records.txt) to store data. This simulates persistent storage similar to databases.

- Create: New users and leave passes are added  
- Read: Data is retrieved when viewing records  
- Update: Leave pass status is modified  
- Delete: (Not implemented but acknowledged as part of CRUD concept)  

### 3. Leave Pass Processing System

Dormers can input details such as date, time out, time in, and reason. The system validates inputs (e.g., correct date format and non-empty fields) before saving them. Each request is automatically assigned a “Pending” status.

### 4. Role-Based Functionalities

- Dormers can submit leave passes, view their records, and search by status  
- Managers can view all submissions, approve or reject requests, and search records  

This demonstrates control flow and conditional logic in programming.

### 5. Input Validation and Error Handling

The system includes validation functions to ensure correct data entry (e.g., date format checking and preventing empty inputs). This improves reliability and reduces incorrect data.

### 6. Basic Data Analysis

The system includes a simple reporting feature that counts the number of pending, approved, and rejected requests.

---

## V. Flowchart

*(Insert your flowchart here)*

---

## VI. Program

**Figure 1:** Registration of Dormer  
**Figure 2:** Dormer submitting leave pass filled in  
**Figure 3:** Registering and logging in as a manager  
**Figure 4:** Manager viewing all leave passes registered by dormers  
**Figure 5:** Leave passes approved  
**Figure 6:** Viewing status of leave pass registered  
**Figure 7:** Searching Leave Pass by name  
**Figure 8:** Logging back in as a dormer to view the status of leavepass  
**Figure 9:** Viewing all leave passes filed by dormer  
**Figure 10:** Searching by status  

---

## VII. Team Roles

**#21 Nambio, Enricha Gemm S.**  
Initiated project planning, assigned tasks, and submitted output  
Managed progress, reminded of deadlines, helped with coding & documentation, submitted output  
Continued coordination, assisted debugging, and paper writing  

**#22 Pedernal, Lucas Íñigo S.**  
System coding (backend development)  
Continued coding (features & improvements)  
Coding + debugging system  
Program >:)  

**#23 Privado, Louise Janine B.**  
Assisted in documentation (proofreading)  
Proofreading & editing paper  
Created and designed presentation slides  

**#24 Rafael, Roswyn Drawde A.**  
System testing, assisted in coding & troubleshooting  
Continued testing & debugging  
Led testing phase, troubleshooting, and submitted output  

**#25 Reyes, Auric Geranyl**  
Assisted in coding  
Assisted in coding  
Assisted in coding  

---

## VIII. References / Background Research (APA Format)

GeeksforGeeks. (2023, July 23). File handling in C++ (with examples). Retrieved April 23, 2026, from https://www.geeksforgeeks.org/file-handling-c-classes/  

Programiz. (n.d.). C++ vectors. Retrieved April 23, 2026, from https://www.programiz.com/cpp-programming/vectors  
