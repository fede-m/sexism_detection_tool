# Sexism Detection Tool
Web application to automatically detect, classify, and explain sexist content in a given text.

This project contains a full-stack application for a tool to detect spans of sexism in text.


## Requirements
### Frontend
#### Installation Setup
- Install Node.js:
    -  install `node` (you can download it from here: https://nodejs.org/en/download)
    - install `npm` (node package manager) --> should be automatically installed with `node`
    - (Optional) install `nvm`(node version manager) to manage the version of node to use in the project.
        - For Windows: install the `nvm-setup.exe` file you find here: https://github.com/coreybutler/nvm-windows/releases and follow the Wizard
    - (Optional) update npm in case you have an old version using `npm install -g npm`
- The React frontend application was created using Vite


#### Versions
- `node`: v22.14.0 (latest LTS version of Node available at the time of creation)
- `npm`: 11.2.0



The project contains:
- `backend`: contains the Python FastAPI backend application to deal with resource intensive applications
- `frontend`: contains the React and Tailwind CSS that define the UI of the application

Virtual environments:
- `pipenv`: for the backend
- `npm`: Node.js is used for the frontend