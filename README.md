### PROFESSIONAL-README-GENERATOR
When creating an open source project on GitHub, it’s important to have a high-quality README for the app. This should include what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions&mdash;this last part increases the likelihood that other developers will contribute to the success of the project. 

You can quickly and easily create a README file by using a command-line application to generate one. This allows the project creator to devote more time to working on the project.

## CRITERIA
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README

## SCREENSHOTS

The following animation demonstrates the application functionality:
![deployed-io](assets/deployed-io.png)
![README-GIF](./Develop/READMEDG.gif)

## CLICK THE ICON BELOW: VIDEO DEMO LINK

[![SC2 Video](./Develop/ICON.PNG)](https://drive.google.com/file/d/1VSKGOEy89UupIsJPT0QLTA-yn6iyaKQ4/view?usp=sharing)

## INSTALLATION

*Steps required to install project and how to get the development environment running:*

To generate your own README, first run `npm install` in order to install the following npm package dependencies as specified in the `package.json`:
  * [`inquirer`](https://www.npmjs.com/package/inquirer) that will prompt you for your inputs from the command line 
  * [`axios`](https://www.npmjs.com/package/axios) to fetch your info from the GitHub API

You can run the app by running  `node index.js` in the terminal.

#### CODE SNIPPETS



**JavaScript | code snippet**

![JS](assets/js-functions.png)

## GitHub Repository & Deployed Site
GitHub: [@danielthomas129](https://api.github.com/users/danielthomas129)
[Github-Repository](https://github.com/danielthomas129/Professional-ReadMe-Generator)
- - -

### Daniel Thomas Guadalupe
  
  ## Questions?
  
  ![Developer Profile Picture](https://avatars3.githubusercontent.com/u/74033385?v=4) 
  
  For any questions, please contact me with the information below:
 
  GitHub: [@danielthomas129](https://api.github.com/users/danielthomas129)
  
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
