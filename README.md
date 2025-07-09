# Exercise 1 Git Merging and Branching

In this exercise, we have learnt how to work on different aspects of one project in a team by learning git 
branching and merging techniques.

Team members:
1. Saima Nasreen.
2. Chandrakant Majumdar.

## Workflow:

Under main branch a git repository Exercise_1_Git is created.<br>
A new branch dev/saima is created which handles the Frontend folder of the app.<br>
Another branch dev/chandra is created which handles the Backend folder of the app.<br>
After working on the respective folder code files, both folders are merged into the main branch.

## Project Structure:

Exercise_1_Git/<br>
├── Frontend_/<br>
│ └── index.html<br>
└── Backend_/<br>
  └── app.py

## Setup Instructions:

1. Clone the repository

`git clone https://github.com/saimanasreen001/Exercise_1_Git.git`<br>
`cd Exercise_1_Git`

### Command to create a new branch

`git branch new-branch-name`

2. Navigate to the respective branches

`git switch dev/saima`<br>
`git switch dev/chandra`<br>

### Command to merge any branch to the main branch

If not main branch, switch to main branch `git switch main`<br>
`git merge dev/saima`<br>
`git merge dev/chandra`<br>


