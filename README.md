**SECTION 1: Prettier and ESLint Extensions**

Prettier and ESLint help maintain clean, consistent, and error-free code in JavaScript and React projects.

*Prettier* is an Automatic code formatter.
Function: Ensures consistent spacing, indentation, and style.
Benefit: Saves on time since code formatting is done automatically.

Example:
function greet(name){console.log("Hello, "+name)}

With Prettier:
function greet(name) {
  console.log("Hello, " + name);
}

*ESLint* is a Code linter for quality and correctness.
Function: Detects errors, unused variables, and enforces best practices.
Benefits: Enforces good coding practices.

Example:
let x = 10
console.log(y) // ESLint: 'y' is not defined

**SECTION 2: Version Control Setup**

*Git* is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
Git allows developers too:
1. Track file changes
2. Save versions of the project
3. Revert to previous versions
4. Modify code/work on different features through branches
5. Collaborate with other developers

*Version Control* is a system that tracks and manages changes made to files overtime.It allows developers to:
1. Save snapshots of their work.
2. Revert to previous versions if needed.
3. Collaborate with others without overwriting each other’s work.

*Git identity Configuration*
Configuring a Git identity means setting your name and email in Git so that every change you save (commit) is recorded as being made by you.

**SECTION 3: JavaScript Runtime & Package Management**

*Node.js* is a JavaScript runtime environment that allows developers to run JavaScript code outside of a web browser.
*npm* is the default package manager that comes with Node.js, used to install and manage JavaScript libraries and dependencies.
*Yarn* is an alternative package manager to npm, designed to be faster, more reliable, and more secure when installing dependencies.
*Package manager*
A packet manager is a tool used to install external libraries, manage project dependencies and update or remove packages when needed.
Why JavaScript projects rely on package managers
1. Reuse of Code
Developers don’t build everything from scratch—they install existing libraries.
2. Dependency Management
Projects often use multiple packages, and package managers keep track of them and ensure the correct versions are installed
3. Speed & Efficiency
Installing packages takes seconds instead of hours/days of coding.
4. Consistency Across Teams
Everyone working on a project installs the same dependencies, avoiding issues.

**SECTION 4: Expo CLI Setup**

*Expo* is a set of tools and services that simplifies building mobile applications using JavaScript and React Native.
*React Native* is the framework used to build mobile apps using JavaScript. *Expo* is a framework built on top of React Native that simplifies mobile app development by abstracting away much of the complexity involved in setting up and managing native projects.
Expo provides a managed workflow that handles native build configurations, dependency management, and tooling (like Xcode and Android Studio), allowing developers to focus on writing JavaScript or TypeScript code. 

**Section 5: Github**

*GitHub* is a cloud-based platform for hosting Git repositories.
it allows collaboration: you can share code, review changes, and contribute to projects online.
*Difference between GitHub and Git*
Git = tool to manage versions of code.
GitHub = online service to store, share, and collaborate on Git-managed projects.
*Pushing code to a remote repository* means sending the changes you’ve made locally on your computer to an online repository like on GitHub, so that others can see, access, and collaborate on your latest version.