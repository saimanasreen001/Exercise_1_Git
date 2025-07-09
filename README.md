# Exercise 1 Git Merging and Branching

In this exercise, we have learnt how to work on different aspects of one project in a team by learning git 
branching and merging techniques.

Team members:
1. Saima Nasreen.
2. Chandrakant Majumdar.

## Workflow:

Under main branch a git repository Exercise_1_Git is created.
A new branch dev/saima is created which handles the Frontend folder of the app.
Another branch dev/chandra is created which handles the Backend folder of the app.
After working on the respective folder code files, both folders are merged into the main branch.

## Project Structure:

Exercise_1_Git/
├── Frontend_/
│ └── index.html
└── Backend_/
  └── app.py

## Setup Instructions:

1. Clone the repository

git clone https://github.com/saimanasreen001/Exercise_1_Git.git
cd Exercise_1_Git

### Command to create a new branch

git branch new-branch-name

2. Navigate to the respective branches

git switch dev/saima
git switch dev/chandra

### Command to merge any branch to the main branch

If not main branch, switch to main branch `git switch main`
`git merge dev/saima`
`git merge dev/chandra`


