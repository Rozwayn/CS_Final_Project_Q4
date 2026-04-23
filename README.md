# Inn ‘n Out: A Digital Leave Pass Management System for Pisay Dormers

## 1. Project Statement / Rationale

Students living in dormitories, especially scholars, experience recurring difficulties in managing leave passes due to the current manual system. Every week, particularly during Fridays and Sundays, dormers are required to line up physically to submit their leave slips. This results in long queues, time pressure, and unnecessary stress, especially for students who are also managing heavy academic workloads.

The manual process also increases the chances of errors, such as illegible handwriting, misplaced records, and delays in approval. These inefficiencies affect both dormers and dorm staff. Dormers lose valuable time that could have been used for studying or resting, while dorm staff struggle to manage and organize large volumes of paper records.

Addressing this problem is important because it directly impacts students’ time management, productivity, and overall well-being. By improving the leave pass system, the project supports a more efficient dormitory process and a better student experience.

## 2. Project Overview and Relevance

The project, Inn ‘n Out, is a digital leave pass management system designed to replace the traditional manual process used by dormers. The system allows users to register, log in, submit leave requests, and track their status, while dorm staff can review, approve, or reject requests through a centralized platform.

This project is highly relevant to Python programming, database management, and data analysis concepts. The system is implemented using structured programming in C++, applying concepts such as file handling, data structures (vectors and structs), and input validation.

Although the current version uses text files as storage, it follows the logic of CRUD operations (Create, Read, Update, Delete), which are essential in database systems. The system also organizes and processes data such as user accounts and leave pass records, demonstrating basic data handling and analysis (e.g., counting approved, pending, and rejected requests).

Overall, the project reflects real-world applications of programming by solving an actual problem using computational methods.

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

## 5. Flowchart

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/0bfcf450-3a42-4c8c-b719-932df1d41d39" />


## 6. Program

**Step 1:** Registration of Dormer 
<img width="315" height="498" alt="image" src="https://github.com/user-attachments/assets/2b801e11-7114-40d7-a980-7ac5228078f8" />

**Step 2:** Dormer submitting leave pass filled in  
<img width="351" height="326" alt="image" src="https://github.com/user-attachments/assets/4ba31d27-c911-472c-ab46-be6266cdf490" />

**Step 3:** Registering and logging in as a manager  
<img width="296" height="604" alt="image" src="https://github.com/user-attachments/assets/338b68dc-4f58-4c5e-95d3-97130ddc7e30" />

**Step 4:** Manager viewing all leave passes registered by dormers 
<img width="290" height="222" alt="image" src="https://github.com/user-attachments/assets/703dd8db-df19-4c73-92d0-e87ee128daf0" />

**Step 5:** Leave passes approved  
<img width="261" height="274" alt="image" src="https://github.com/user-attachments/assets/100d3f1a-e26d-43e8-8c1b-6541a35a95ce" />

**Step 6:** Viewing status of leave pass registered  
<img width="335" height="222" alt="image" src="https://github.com/user-attachments/assets/c7440751-e87d-43b4-8d08-a30b900ad210" />

**Step 7:** Searching Leave Pass by name 
<img width="256" height="261" alt="image" src="https://github.com/user-attachments/assets/662879d8-af02-42c3-98d0-72a5a8c5640f" />

**Step 8:** Logging back in as a dormer to view the status of leavepass  
<img width="258" height="387" alt="image" src="https://github.com/user-attachments/assets/0dc08dcb-e418-42a2-abbb-05b9089cffc4" />

**Step 9:** Viewing all leave passes filed by dormer  
<img width="230" height="292" alt="image" src="https://github.com/user-attachments/assets/3f9f7c61-5d84-44ca-8540-b65b33fc1313" />

**Step 10:** Searching by status  
<img width="490" height="224" alt="image" src="https://github.com/user-attachments/assets/18b0efb6-2137-4abf-8ec6-4efc149e552b" />


## 7. Team Roles

**Nambio, Enricha Gemm S.**  
21 served as the Project Lead, consistently initiating tasks, assigning responsibilities, and ensuring deadlines were met. They were also responsible for submitting outputs for Quarters 1, 2, and 4, contributed to coding, and led the development of the final paper and assisted in presentation preparation.

**Pedernal, Lucas Íñigo S.**  
22 acted as the Main Programmer, handling the system’s development throughout all four quarters, including backend coding, feature implementation, and debugging.

**Privado, Louise Janine B.**  
23 focused on Documentation and Presentation, primarily proofreading the paper and creating and designing the group’s presentation slides.

**Rafael, Roswyn Drawde A.**  
24 worked as the Tester and Support Developer, assisting in coding and troubleshooting, leading system testing, and submitting the Quarter 3 output.

**Reyes, Auric Geranyl**  
25 contributed as a Support Programmer, assisting in coding tasks across the project.  

## 8. References / Background Research (APA Format)

GeeksforGeeks. (2023, July 23). File handling in C++ (with examples). Retrieved April 23, 2026, from https://www.geeksforgeeks.org/file-handling-c-classes/  

Programiz. (n.d.). C++ vectors. Retrieved April 23, 2026, from https://www.programiz.com/cpp-programming/vectors
