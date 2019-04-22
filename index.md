# Manoa Study Hub

## Table of Contents

1. [Overview](#overview)
2. [User Guide](#user-guide)
3. [Developer Guide](#developer-guide)
    3. [Installation](#installation)
4. [Development History](#development-history)
    4. [Milestone 1](#milestone-1)
        4. [Mock-Up Pages](#mock-up-pages)
        4. [Utilizing Github Issues](#utilizing-github-issues)
    4. [Milestone 2](#milestone-2)
    4. [Milestone 3](#milestone-3)
5. [Team](#Team)
    5. [Goals](#Goals)
    5. [Team Bios](#Team-Bios)

## Overview

Manoa Study Hub will eventually provide a platform for students to organize study groups with each other in order to work on assignments, projects, or to prepare for tests. We hope that this web application will help students find fellow students and tutors through our create and attend study session features. In addition, this web application will help students keep track of current study sessions as well as other students or tutors they've met in previous or future study sessions.

Manoa Study Hub can be accessed through this [link](http://manoastudyhub.meteorapp.com/#/).

## User Guide

#### Landing Page
<img class="ui left floated image" src="/images/m2/landing-m2.JPG" width="600">
<p>
When you first visit our site you are taken to the landing page, where you can read a brief description about Manoa Study Hub as well as some of the functionalities that our site can provide. From this page you are able to use the Login button which presents you with a dropdown menu that allows you to either sign in or sign up for a new account.
</p>

#### Sign Up Page
<img class="ui medium left floated image" src="/images/m2/signup-m2.JPG" width="600">
<p>
After clicking the Login button on the landing page, if you selected the option to sign up- this is the page you would be rerouted to. On this page you are able to enter your preferred email address as well as a password and submit when you have completed inputting your registration information. If you realize that you already have an account with us you are able to use the "Login here" option which would then reroute you to the sign in page.
</p>

#### Sign In Page
<img class="ui medium left floated image" src="/images/m2/signin-m2.JPG" width="600">
<p>
After clicking the Login button on the landing page, if you selected the option to sign in- this is the page you would be rereouted to. On this page you are able to enter the information of the existing account that you previously created, which would include your email and password. After you may click the "submit" button to proceed into the main site. If you suddenly realize that you did not have a pre-existing account with us you are able to use the "Click Here to Register" option which would then reroute you to the sign up page.
</p>

#### User Home Page
<img class="ui medium left floated image" src="/images/m2/userlanding-m2.JPG" width="600">
<p>
After successfully signing in or signing up you are taken to the user home page which looks similar to the intitial landing page- however it now comes equipped with a navigation bar and shows the email of the user who is logged in. The nav bar has options of other pages to be reouted to which include: the User Page, Profile page, Calendar page, Study Sessions page, Add Study Session page, as well as the "Manoa Study Hub" words which double as a link back to the user home page (this page) from any of the other pages, and the email of the user who is logged in which- when clicked provides the option to log out. This page also gives a brief overview of the site as well as gives information on some of the functionalities of the site.
</p>

#### User Page 
<img class="ui medium left floated image" src="/images/m2/userpage-m2.JPG" width="600">
<p>
After clicking on the User Page option on the nav bar you are taken to this page. At the top of this page you can view the main components of the site which include the "My Profile", "My Calendar", and "My Study Sessions" pages which are buttons that will reroute you to their respective pages. It also allows you to view the upcoming study sessions in a list format with a view session button that will allow a popup window to show the card of more in-depth detail about the study session. It also has a category to show the other students who are planning on attending which will likely be equipped with a button to view the profiles of the other students in the future.
</p>

#### Profile Page
<img class="ui medium left floated image" src="/images/m2/profile-m2.JPG" width="600">
<p>
After clicking on the Profile page option on the nav bar you are taken to this page. This page shows the profile of the user who is logged in which includes details like their name, major, class standing, subjects, and a description about themselves. It should eventually be equipped with an edit button to allow the user to make changes.
</p>

#### Calendar Page
<img class="ui medium left floated image" src="/images/m2/calendar-m2.JPG" width="600">
<p>
After clicking on the Calendar page option on the nav bar you are taken to this page. On this page you are able to view a calendar which will show the previous, current, and upcoming study sessions. You are able to utilize the buttons at the top of the page to see different views of the calendar by month, week, or day as well as previous or future months. You can also click on a day to add a study session which will pop up a confirmation window.
</p>

#### List Study Sessions Page
<img class="ui medium left floated image" src="/images/m2/liststudysession-m2.JPG" width="600">
<p>
After clicking on the Study Sessions page option on the nav bar you are taken to this page. On this page you are able to view the cards of study sessions that have already been created. You are able to view all of the information that you should need in order to decide whether or not you wish to attend this study session. Should you choose to attend, you can use the attend button which will then give you an alert at the top of the screen which states that your session has been added to the sessions that you plan on attending. There is also an option to allow the user to edit the sessions that they have created. Upon clicking the edit button you are rereouted to the edit study session page which which will be filled out with the previously added information that you are able to edit. After hitting the submit button your changes are added and an alert tells you that your updates have been made.
</p>

#### Add Study Session Page
<img class="ui medium left floated image" src="/images/m2/addstudysession-m2.JPG" width="600">
<p>
After clicking on the Add Study Session page on the nav bar you are taken to this page. On this page you are able to fill out all of the fields that provide information about the study session you are creating. These fields include first name, last name, created by, date, location, and the course. After filling out all of the fields you can then use the submit button which will then create an alert telling you that your session has been added if all of the information was added correctly.
</p>

#### Admin Page
<img class="ui medium left floated image" src="/images/m2/admin-m2.JPG" width="600">
After logging in as an admin you are able to view this page which lists all of the upcoming sessions and students. From this page the admin is able to view all of the sessions and will eventually be able to delete them if they wish to. 

#### Sign Out Page
<img class="ui medium left floated image" src="/images/m2/signout-m2.JPG" width="600">
<p>
Upon clicking on the email of the user that is logged in you are given a drop down window that gives you the option to log out, which when clicked will reroute you to this page after you have successfully logged out.
</p>

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
    
Our work on Milestone 2 started on 4/8 and finished on 4/21. Here is our [M2 project](https://github.com/manoastudyhub/code-directory/projects/2) which contains all of the issues we worked on for Milestone 2.

<img class="ui medium left floated image" src="/images/m2done.png" width="650">

### Milestone 3
    
Our work on Milestone 2 started on 4/21 and is still in progress. So far we have created a [M3 project](https://github.com/manoastudyhub/code-directory/projects/3) which contains all of the issues we'll be working on for Milestone 3.

<img class="ui medium left floated image" src="/images/m3.png" width="650">

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

