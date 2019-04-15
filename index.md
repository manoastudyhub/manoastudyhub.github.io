# Manoa Study Hub

## Table of Contents

1. [About Manoa Study Hub](#about-manoa-study-hub)
2. [Developer Guide](#developer-guide)
    2. [Installation](#installation)
3. [Development History](#development-history)
    3. [Milestone 1](#milestone-1)
        3. [Mock-Up Pages](#mock-up-pages)
        3. [Utilizing Github Issues](#utilizing-github-issues)
    3. [Milestone 2](#milestone-2)
4. [Team](#Team)
    4. [Goals](#Goals)
    4. [Team Bios](#Team-Bios)

## About Manoa Study Hub

Manoa Study Hub will eventually provide a platform for students to organize study groups with each other while having in-person interactions in order to work on assignments, projects, or to prepare for tests. 

## Developer Guide

### Installation

1. In order to begin using the application you will need to <a href="https://www.meteor.com/install"> install Meteor </a>

2. Next, you will need to <a href="https://github.com/manoastudyhub/code-directory">download</a> a copy of Manoa Study Hub.
You should note that you may need to request permission from the authors in order to access the repo.

3. Then, in the command prompt you will need to cd into the app directory (within the code-directory file) and install the Meteor library as follows: 
    <p>
      <code> meteor npm install </code>
    </p>
 
4. After Meteor has been installed, you can then run the application by using:
    <p>
      <code>meteor npm run start</code>
    </p>

5. After the app runs for the first time, it will create some default data and users. The output should look as follows:
    <p>
      <img src="/images/meteorfirstrun.JPG" alt="meteor first run image" width="470" height="315">
    </p>
    <p>
      *It is important to note that there is a <b>bcrypt warning</b> which will try to encourage you to use bcrypt. However it is difficult to install bcrypt with Windows operating systems. Bcrypt is unneccesary for the purposes that we are using for so it is okay to just ignore this warning, it will not interfere with the use of the application.
    </p>
 
6. If there are no errors, the template application will appear at <a href="http://localhost:3000/">http://localhost:3000/</a>. You can then login by using one of the default accounts at <a href="https://github.com/ics-software-engineering/meteor-application-template-react/blob/master/config/settings.development.json">settings.development.json</a>.

7.You can also use ESLint in the imports directory to check for general errors by using:
      <code>
        meteor npm run lint
      </code>

## Development History

Throughout the development process, we conformed to the <a href="http://courses.ics.hawaii.edu/ics314f16/morea/project-management/reading-guidelines-idpm.html">Issue Driven Project Management (IDPM)</a> guidelines. In summary, this means that the team effectively communicated with each other at least twice a week, milestones were accomplished in sets of tasks that were divided into approximately 2-3 days of work which were assigned in <a href="https://github.com/manoastudyhub/code-directory/projects">github projects</a> as issues. Each team member is ultimately responsible for at least 2 issues during each milestone and must have them completed before the deadlines.

The development history of Manoa Study Hub is shown in the following milestone sections.

### Milestone 1

This Milestone began on April 1, 2019 and ended on April 10, 2019.

The goals of this Milestone included creating mock up pages, utilizing Github projects and issues to help manage the development process for this project, and learning how to deploy our project to Galaxy.

#### Mock-Up Pages

Mockups for the following pages were created during Milestone 1 and have been deployed to Galaxy:

<a href="http://manoastudyhub.meteorapp.com/#/">Landing Page</a>

<img class="ui medium left floated image" src="/images/landing-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/signin">Sign In Page </a>

<img class="ui medium left floated image" src="/images/signin-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/signout">Sign Out Page</a>

<img class="ui medium left floated image" src="/images/signout-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/">Student Homepage</a>

<img class="ui medium left floated image" src="/images/student-home-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/">Admin Homepage</a>

<img class="ui medium left floated image" src="/images/admin-home-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/userPage">User Page</a>

<img class="ui medium left floated image" src="/images/userpage-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/userPage">Profile Page</a>

<img class="ui medium left floated image" src="/images/profile-deployed.JPG" width="400">

Calendar - Not yet deployed to Galaxy

<img class="ui medium left floated image" src="/images/calendar.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/add">Add Study Sesh Page</a>

<img class="ui medium left floated image" src="/images/addstudysesh-deployed.JPG" width="400">

<a href="http://manoastudyhub.meteorapp.com/#/studyList">List Study Sesh Page</a>

<img class="ui medium left floated image" src="/images/liststudysesh-deployed.JPG" width="400">

#### Utilizing Github Issues

In Milestone 1 we implemented the <a href="https://github.com/manoastudyhub/code-directory/issues">Github issues</a> as shown below:

<img class="ui medium left floated image" src="/images/milestone1.JPG" width="650">

In Milestone 1, we also created and resloved 13 issues that dealt with creating the mockup pages and the basis of our site's collections. These issues were monitored through the <a href="https://github.com/manoastudyhub/code-directory/projects/1">Project M1</a>:

<img class="ui medium left floated image" src="/images/github-issues-progress.JPG" width="650">

Each Issue was implemented in it's own branch and was merged with the master:

<a href="https://github.com/manoastudyhub/code-directory/network"><img class="ui medium left floated image" src="/images/github-merged.JPG" width="650"></a>

### Milestone 2
    
Our work on Milestone 2 started on 4/8 and is still in progress. So far we have created a [M2 project](https://github.com/manoastudyhub/code-directory/projects/2) which contains all of the issues we'll be working on for Milestone 2.

<img class="ui medium left floated image" src="/images/m2.png" width="650">

## Team

### Goals

The goals that our group has for this project involves: gaining experience working as a group, creating a large-scale project, and learn and use new coding components. Most assignments in class so far have been individual work and so we want to learn how to coordinate with other people in order to achieve a final project. In addition, some of us believe this is a good opportunity to work on a large-scale project in comparison to the smaller assignments done throughout the semester. Finally, another goal we have is to learn new things and expand on the knowledge gained throughout the semester in areas such as React and Semantic UI.

### Team Bios

<img class="ui medium left floated image" src="/images/Tyler.jpg" width="200">
**Tyler Chinen**

Some skills that I would like to develop through working on this project would be to gain experience with working in groups. I would also like to enhance my skills of working with Meteor, Github, and Javascript. Some skills that I bring to the team are that I am acquainted with the concepts and areas that we have covered throughout this course.


<img class="ui medium left floated image" src="/images/Ty.jpg" width="200">
**Ty Yamasaki**

What I hope to gain most by working on this project is experience working with a larger project with multiple team members, specifically with how to cooperate and communicate effectively and how to work with others through Github. I also want to improve my ability to work with Meteor and React. In terms of skillsets, I am capable of working with any of the material that was covered during the class.

<img class="ui medium left floated image" src="/images/angeli.jpg" width="200">
**Angeli Amascual**

I’m familiar with all the topics we’ve learned throughout the semester such as Javascript, html, react, semantic ui, meteor, etc. I wish to gain experience with working as a group. From this I hope to learn about task distribution amongst members in a team, time management and deadline awareness for completing tasks, and learning how to reconvene with fellow team members in order to produce a single project.

<img class="ui medium left floated image" src="/images/lance.jpg" width="200">
**Lance Hwang**

With this, project, I hope to develop skills in time management and coordinating myself in a group coding environment.  I am familiar with a handful of the concepts covered in class and I hope to contribute with what I learned throughout the semester.

<img class="ui medium left floated image" src="/images/maxDeyoProfilePic.jpg" width="200">
**Max Deyo**

Over the course of this project I hope to gain experience working in a team, using Github for version control and task management and managing time and deadlines. I also hope to further develop my skills working with Javascript, React, HTML/CSS and Meteor.

