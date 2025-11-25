# college-study-planner
Project Name:college study planner, Created by:Harshvardhan Singh-VIT Bhopal
1.What the project does?
As the name suggests,the project gives design the study planner for college.The College Study Planner project is a command-line application designed to help a college student manage and organize their academic tasks, assignments, and projects.
It functions as a persistent digital to-do list, allowing the user to track their study workload across different subjects.
2.Why is the project useful?
The College Study Planner project is incredibly useful because it serves as a practical, tangible capstone for learning fundamental programming concepts while also delivering genuine real-world utility for a student.
3.How can the user get started with the project?

Here is a step-by-step guide for the user:
Step 1: Save the Code
Create a File: Open a text editor (like VS Code, Notepad++, or Sublime Text) and save the entire Python code provided above into a new file.

Name the File: The file must be saved as study_planner.py.

Step 2: Run the Program
Open Terminal/Command Prompt: Navigate to the folder where you saved study_planner.py using your computer's terminal (Command Prompt on Windows, Terminal on Mac/Linux).

Execute the Script: Run the program using the Python interpreter:

Bash

python study_planner.py
First Run: The program will print a message: "No previous task file found. Starting a new planner."

File Creation: A new file named tasks.json will automatically be created in the same folder to store your tasks permanently.

2. Interacting with the Planner
Once the program is running, you will be presented with the main menu and can interact with the system by entering the corresponding numbers (1 through 6).

A. Adding Tasks (Option 1)
This is the first action most users will take. The program will prompt you for the necessary details:

Input Prompt	Example Input	Notes
Task Name	Final Essay Draft	The descriptive name of the work.
Subject/Course	History 101	The academic course it belongs to.
Deadline (YYYY-MM-DD)	2025-12-15	Crucial: Must follow this format.
Priority (1: High, 2: Medium, 3: Low)	1	Enter the number corresponding to the priority.

After entering a task, the program automatically saves it to tasks.json and returns to the main menu.

B. Viewing Tasks (Options 2 & 3)
Option 2 (View Pending Tasks): Shows only tasks that are not yet completed. These are automatically sorted by their deadline.

Option 3 (View All Tasks): Shows all entries, including those marked as complete, allowing you to see your historical progress.

C. Updating Tasks (Options 4 & 5)
When marking a task complete or deleting it, the program uses the index
number shown on the screen, not the internal ID number.

Mark Task as Complete (Option 4):

The planner first displays the list of pending tasks.

You enter the input

index
number shown next to the task you finished (e.g., if the task is listed as [01], you enter 1).

Delete Task (Option 5):

The planner first displays all tasks (pending and complete).

You enter the input

index
number shown next to the task you want to permanently remove.

D. Exiting the Program (Option 6)
Choosing Option 6 exits the loop and terminates the program. All tasks are automatically saved to tasks.json upon exit, ensuring data persistence.
