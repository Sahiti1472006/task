Personal Task Manager
A simple console-based Java application that helps users manage their daily tasks efficiently. This project allows users to add, view, update, delete, and sort tasks based on priority or due date.
Features
✅ Add Tasks – Users can add tasks with a name, due date, and priority (High/Medium/Low).
✅ View Tasks – Displays a list of all tasks with their details.
✅ Update Tasks – Users can update the task name, due date, or priority.
✅ Delete Tasks – Removes a task from the list based on its ID.
✅ Sort Tasks – Tasks can be sorted by priority or due date.
✅ User-Friendly Console Interface – Easy-to-use text-based menu system.
✅ Basic Error Handling – Prevents invalid inputs and handles missing tasks.
Technologies Used
• Java (JDK 8 or later)
• ArrayList for in-memory storage
• Comparator for sorting tasks
• Scanner (System.in) for user input
How to Run the Project
### Prerequisites
Ensure Java (JDK) is installed. Check using:
java -version
If Java is not installed, download it from Oracle JDK: https://www.oracle.com/java/technologies/javase-downloads.html
Steps to Run
Clone the Repository:
git clone https://github.com/your-username/Personal-Task-Manager.git
cd Personal-Task-Manager
Compile the Code:
javac TaskManagementSystem.java
Run the Program:
java TaskManagementSystem
Usage Guide
### Main Menu
When you run the program, you'll see the following options:
1. Add Task
2. View Tasks
3. Update Task
4. Delete Task
5. Sort by Priority
6. Sort by Due Date
7. Exit
Example Usage
#### 1️⃣ Add a Task
Example Input:
Enter task name: Complete Java Project
Enter due date (YYYY-MM-DD): 2025-03-20
Enter priority (High/Medium/Low): High
✅ Output: Task added successfully!
#### 2️⃣ View Tasks
Example Output:
TaskID: 1, Name: Complete Java Project, Due: 2025-03-20, Priority: High
#### 3️⃣ Update a Task
Example Input:
Enter task ID to update: 1
Enter new task name (leave blank to keep unchanged): Complete Java Assignment
Enter new due date (leave blank to keep unchanged): 
Enter new priority (leave blank to keep unchanged): Medium
✅ Output: Task updated successfully!
#### 4️⃣ Delete a Task
Example Input:
Enter task ID to delete: 1
✅ Output: Task deleted successfully!
#### 5️⃣ Sort by Priority
Sorts tasks by priority (High → Medium → Low).
#### 6️⃣ Sort by Due Date
Sorts tasks by due date (earliest first).
#### 7️⃣ Exit the Program
Closes the application
