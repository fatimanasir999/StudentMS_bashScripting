# StudentMS_bashScripting 

This **Student Management System** is a practical project built using **Bash scripting** on the **Ubuntu** operating system. The system functions entirely in the terminal and demonstrates the use of **basic file management**, **user interaction**, and **validation techniques** in shell scripting. It provides two primary user roles: **Teacher** and **Student**, each with distinct capabilities for managing and viewing student data.

### System Features:

#### **For Teachers:**
- **Add New Student Records**: Teachers can input student details such as roll number, name, and other relevant information to create new student records.
- **Update Student Information**: Teachers have the ability to modify any student’s data, such as updating personal details or academic records.
- **Delete Student Records**: Teachers can remove student records from the system based on the roll number.
- **Assign Marks and Grades**: Teachers can enter specific marks for students and assign grades accordingly. The marks are stored for each student, and grades can be calculated based on preset criteria.
- **Generate Student Reports**: Teachers can generate performance reports for students, displaying their marks, grades, and overall performance.
- **Teacher Login with Password**: The system requires a password for teachers to ensure secure access. Teachers can only perform administrative actions after entering the correct password.
- **Roll Number Validation**: Before updating or deleting records, the system checks if the provided roll number is valid and exists in the records.

#### **For Students:**
- **View Marks**: Students can check the marks assigned to them for individual subjects or overall performance.
- **View Grades**: Based on the marks assigned, students can see their grades, which help them understand their academic standing.
- **Roll Number and Access Control**: Students can only view their own marks and grades, with proper validation to ensure their roll number is correct before displaying any information.

### How It Works:
The system uses simple text files to store all student data, such as personal information, marks, and grades. The data is organized in a way that allows easy retrieval and updating using the shell script. The teacher’s password and roll number checks ensure that unauthorized users cannot modify or access records they aren’t allowed to.

### User Interaction:
- The system prompts users to select their role (Teacher or Student) upon startup.
- Teachers are prompted to enter a password for authentication.
- Students are asked to input their roll number to access their information.
- After authentication, users are shown a menu of available actions based on their role.

### Benefits:
- **File Handling**: Demonstrates efficient file reading, writing, and updating in a shell environment.
- **User Input Validation**: Ensures that all user inputs (like roll numbers or passwords) are checked for correctness before any operation is performed.
- **Basic Database Simulation**: The system simulates a rudimentary database using text files, where each student’s data is stored and can be retrieved or modified.

This project is a perfect example for learning the basics of scripting, file management, and simple validation checks within the Linux terminal.

