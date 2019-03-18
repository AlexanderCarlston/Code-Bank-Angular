# Code Bank

> Ultimate storage and export of github gists.

<!-- TOC -->

- [Navigation](#navigation)
    - [Intro](#intro)
    - [Technology](#technology)
    - [Project Managment](#project-managment)
    - [Orignal Project](#original-vue-project)
    - [Minimum Viable Product](#mvp-functionality)
    - [Design Inspiration](#design-inspiration)
    - [Design Planning](#design-planning)

<!-- /TOC -->

## Intro

This project started as my capstone project for Galvanize, a end of class project where I dived in to unfimilar technologies to make a Miniumum Viable Product that I would show case in front of an audience. I succesfully completed this, but didn't have the experience to fully flesh out my idea. After 7 months of experience I'm coming back to make the complete product that I wanted to when I started this project.

## Technology

* [Angular 7](https://angular.io/) - Front End Framework
* [NGXS](https://github.com/ngxs/store) - State Management
* [Clarity Deisgn](https://clarity.design/) - Design Framework (CSS)
* [SCSS](https://sass-lang.com/guide) - Preprocessor

## Project Managment

* [Kanban Board](https://waffle.io/AlexanderCarlston/Code-Bank-Angular) - My Kanban Board
* [Wireframe](https://www.figma.com/file/aijDn8RZjWPCgT5fNQs3MWHS/Code-Bank?node-id=0%3A1) - My wireframing tool

## Original Vue Project

https://github.com/AlexanderCarlston/CODE-BANK
<br>
This is the original project done in Vue/Vuex/Vuetify and more. I'm starting a job in Angular 7 so that's the reason why I'm switching to the current technology.

## MVP Functionality
As a user I want to be able to import my gists from Github. (OAuth sign in)
<br>
As a user I want to be able to select which gists I import. 
<br>
As a user I want to be able to store my gists from Github.
<br>
As a user I want to be able to categorize my gists. 
<br>
As a user I want to be able to export my categorized gists into a npm package. (JavaScript Vaults)

## Design Inspiration

### Header

Since I'm using Clarity Design, I decided to use their documentation for inspiration. I used their header as an example of how to do a responsive header.
<br>
![Header](https://imgur.com/JjzhGww.png)
<br>
Header on mobile:
<br>
![Mobile](https://imgur.com/BBsEnBg.png)

## Design Planning

### Header

![Header](https://imgur.com/YKPuGZu.png)

![Responsive](https://imgur.com/UOhmKwz.png)

### Landing Page

The main purpose of the landing page is to introduce people to the website. With that in mind basic info, and the explanation of why Code Bank exists should be made. 

### Bank

The bank is where the storage of gists happen, will have to implement a library and figure out how to do tags.

### Vault

Vaults are the exportation of gists, and will have to make a npm package that handles all of this