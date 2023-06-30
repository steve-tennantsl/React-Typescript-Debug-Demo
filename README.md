# Debugging Unit Tests

This project demonstrates the config needed to debug into unit tests while using TypeScript. To do so simply place a breakpoint in the App.test.tsx file and use the 'Debug test single run' configuration in your Run and Debug window in Visual Studio Code. Make sure you run an npm install if this is your first time loading the project.

The configuration for the debug run can be found in the .vscode/ launch.json file. This configuration is based on a tutorial that can be found [here](https://www.basefactor.com/using-visual-studio-code-to-debug-jest-based-unit-tests).