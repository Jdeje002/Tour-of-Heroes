# Tour of Heros tutorial. 
## Introduction 
### 1. What we will be learning 
+ Use built-in Angular directives to show and hide elements and display lists of hero data.
+ Create Angular components to display hero details and show an array of heroes.
+ Use one-way data binding for read-only data.
+ Add editable fields to update a model with two-way data binding.
+ Bind component methods to user events, like keystrokes and clicks.
+ Enable users to select a hero from a master list and edit that hero in the details view.
+ Format data with pipes.
+ Create a shared service to assemble the heroes.
+ Use routing to navigate among different views and their components.

### 2. Layout of page and example 
    Page example of how the project will look
<img src="https://angular.io/generated/images/guide/toh/nav-diagram.png" />
    Walk through on the functionality of the page after its done.
<img src="https://angular.io/generated/images/guide/toh/toh-anim.gif" />

## Creating the project.
    Steps to create the new project 
+ Set up your environment.
+ Create a new workspace and initial application project.
+ Serve the application.
+ Make changes to the application.

### Code to start
    In the CLI of the project do the following 
1. Ensure that you are not already in an Angular workspace folder. For example, if you have previously created the Getting Started workspace, change to the parent of that folder.
2. Run the CLI command ng new and provide the name angular-tour-of-heroes, as shown here:
``` ng new angular-tour-of-heroes ```
3. The ng new command prompts you for information about features to include in the initial application project. Accept the defaults by pressing the Enter or Return key.