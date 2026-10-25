# git-project

CS-408 Advanced Web Development, Assignment 1.

A small Node.js project that demonstrates a development environment setup and a Git/GitHub workflow.

## Project Files

- `app.js`: basic Node.js script
- `index.html`: test web page used to practise debugging with browser Developer Tools
- `package.json` and `package-lock.json`: project metadata, dependencies and exact versions
- `.gitignore`: excludes `node_modules/` from version control

## Requirements

- Node.js and npm
- Git
- VS Code

## Setup

1. Clone the repository:
   git clone https://github.com/saira-99/git-project.git
2. Move into the folder:
   cd git-project
3. Install dependencies:
   npm install
4. Run the app:
   node app.js

## Dependencies

- `express`: runtime dependency
- `nodemon`: development dependency (auto-restarts the app during development)

## Git Workflow

- `main`: stable branch
- `feature-branch`: used to add and test changes before merging into `main`
