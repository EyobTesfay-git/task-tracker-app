# task-tracker-app
Final Project Report: Solo Submission
Project Overview
Project Name: Task Tracker App
Team Members: Eyob Tesfay (solo)
One-Sentence Description: A simple web app to track tasks, mark them complete, and delete
them as needed.
Project Goals
By the end of this project, I aimed to create a working task management app that allows users
to:
● Add tasks with text input
● Mark tasks as completed
● Delete tasks
● View all tasks in a list
User Stories
Must Have
● As a user, I want to add a task, so that I can keep track of what I need to do.
● As a user, I want to mark a task as complete, so that I can track progress.
● As a user, I want to delete a task, so that I can remove completed or unwanted items.
Nice to Have
● As a user, I want tasks to persist after refreshing the page, so that I don’t lose my list.
● As a user, I want tasks to display immediately after adding or deleting them, so that the
app feels responsive.
Tasks & Git Workflow
Development Process:
1. Created a main branch for safe, working code.
2. Created feature branches for each task:
○ feature/add-task
○ feature/complete-task
○ feature/delete-task
3. Developed each feature on its branch, committing frequently with descriptive messages.
4. Created pull requests to merge completed features into main.
5. Reviewed code and resolved minor merge conflicts when they occurred.
Testing
Manual Testing Checklist
● Add tasks with normal text
● Add tasks with numbers
● Add tasks with special characters
● Prevent empty tasks
● Tasks appear in the list immediately
● Delete tasks works correctly
● Works in Chrome and Firefox
Automated Testing
Python Example:
def test_add_task():
task = create_task("Test Task")
assert task["text"] == "Test Task", "Task text should match"
Result: All tests passed successfully.
Documentation
README.md: Includes:
● Project overview
● Instructions to run the project
● Installation steps
● Testing instructions
● Team member information (solo in this case)
Project Assets
● Screenshots captured for all major features
● Optional: simple demo video prepared for presentation
Sprint Review & Retrospective
What was planned: Add, complete, delete tasks.
What was accomplished: Successfully implemented all planned features.
Challenges: Minor merge conflicts when experimenting with task deletion. Resolved by careful
review.
What went well: Git workflow and feature branches worked smoothly.
Lessons learned: Even as a solo developer, using Git branches and pull requests keeps code
organized.
Presentation Plan
● Slide 1: Title, project name, solo developer info
● Slide 2: Problem solved – keeping track of tasks easily
● Slide 3: Live demo of adding, completing, deleting tasks
● Slide 4: Development process – Agile workflow and Git history
● Slide 5: Lessons learned and challenges overcome
● Slide 6: Next steps – optional improvements like task persistence
Technologies Used
● HTML, CSS, JavaScript
● Python (for testing scripts)
● Git & GitHub
Future Improvements
● Task persistence after page refresh
● Task prioritization and sorting
● Responsive design for mobile devices
