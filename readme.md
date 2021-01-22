# Needs tools

Visual Studio Code: https://code.visualstudio.com/
NPM: https://www.npmjs.com/get-npm


# The project

Once Visual Studio Code is installed, open the file "workspace.code-workspace", to open the project. Within it, open the terminal via Ctrl+\` and run the NPM commands to build/run.

Once you are happy with a build, copy the /profile-app/build contents to the /docs folder. To use this (/docs) folder as our github page hosting folder, ensure your repository / Settings / GitHub Pages / Source is "/docs".


# Command Cheatsheet

build: npm run-script build
run: npm run-script start


# To create project from scratch

npm install -g create-react-app  
npx create-react-app my-app  
cd my-app  
npm start
