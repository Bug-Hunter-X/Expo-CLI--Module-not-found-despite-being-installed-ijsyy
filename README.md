# Expo CLI Module Resolution Error

This repository demonstrates a peculiar issue encountered with the Expo CLI where a module, despite being correctly installed and listed in `package.json`, is reported as missing by the CLI during the `expo start` process.

The problem is that standard troubleshooting steps such as clearing the cache (`expo start --clear`) and reinstalling modules did not resolve the issue.  The app itself functioned correctly when run on both emulators and physical devices, suggesting that the issue was isolated to the Expo CLI's module resolution mechanism.

The `bug.js` file shows the original code containing the problematic module import.  The `bugSolution.js` file (if a solution was found) outlines steps to resolve the problem.