# Exam 1

> Adding name verification, age validation, and the delivery of a survey to project.

## Getting Started

<p> These instructions will allow you to preview the proposed features code.

### Prerequisites

<p> The things you need to start.

- A logged in GitHub account
- A local IDE/Code Editor with a folder for the project
- A main, develop, and feature/template branch in your repository.

### Installation

<p> A step by step guide that will tell you how to get the development environment up and running.

```
$ First step - Be on your feature/template branch and add welcome.js and getName.js files to your folder. The welcome.js file should include the following:
    import { verifyName } from './getName.js';
    console.log("=".repeat(35));
    console.log("Welcome to eligibility check");
    console.log("=".repeat(35));
    console.log("\n");
    const userName = verifyName(username);
    console.log(`Hello ${userName}!\n`);
The getName.js file should include the following:
    export function verifyName() {
    const input = prompt("Enter your age: ");
    return input;
}
$ Second Step - Add your changes via the terminal command:
    git add welcome.js getName.js
Then check the status with:
    git status
Then create your message for your commit like so:
    git commit -m “([Your Name]) Feature-A: Show a greeting message to user and ask for their name."
Then you'll actually push the commit with:
    git push --set-upstream origin feature-a
$ Third Step - After pushing your code check your repository to make sure it reflects your commits; then compare and approve your pull request
```

## Usage

A few examples of useful commands and/or tasks.

```
$ Make sure you switch the base branch from 'main' to 'develop' when on the 'Comparing Changes' page
```

### Branches

- main
- Develop
- commit-template
