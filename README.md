# The Baseball Chronicles
## A website built about the history of baseball

![Mockup image](assets/docs/am-i-responsive.png)

(Developer: Alexander Strauch)

## **[Live site](https://alexstrauch.github.io/baseball-chronicles/index.html)**

## Table of contents

1. [Introduction](#introduction)
    - [Project description](#project-description)
    - [Purpose](#purpose)
2. [UX](#ux)
    - [User demographic](#user-demo)
    - [User goals](#user-goals)
    - [User expectations](#user-expectations)
    - [User stories](#user-stories)
3. [Design](#design)
    - [Design choices](#design-choice)
    - [Fonts](#fonts)
    - [Colors](#colors)
    - [Layout](#layout)
    - [Wireframes](#wireframes)
4. [Features](#features)
    - [Core functionalities](#core-function)
    - [Screenshots](#screenshots)
5. [Future features](#future-features)
6. [Languages used](#languagues)
7. [Technologies used](#technologies)
8. [Testing](#testing)
    - [HTML validation](#html-validation)
    - [CSS validation](#css-validation)
    - [Performance](#performance)
    - [Accessibility](#accessibility)
9. [Bugs](#bugs)
10. [Deployment](#deployment)
11. [Credits](#credits)
12. [Resources](#resources)
13. [Acknowledgements](#acknowledgements)

## Introduction

### Project description

- The Baseball Chronicles is a web application that offers users an in-depth look at baseball’s most memorable moments, players, and statistics. 

### Purpose
- The purpose of the project is to make baseball history accessible and visually engaging, providing users with curated content about the sport’s past and present. The platform was built to preserve the essence of baseball by showcasing data-driven insights, historical recaps, and player profiles.

[Back to table of contents](#table-of-contents)

## UX

### User demographic

- This project is intended for baseball fans and newcomers of all ages who want to dive deeper into the history of the sport.

### User goals

- Dive into detailed historical data about past seasons, legendary games, and player achievements.

- Discover iconic baseball games, historical records and key milestones

- Stay updated with recent and historical events

- Compare the statistics of the greatest players of all time

### User expectations

- Accessible website on all devices

- Responsive design on all devices without layout or performance issues

- User-friendly interface with easy access to the provided information

- Links and features that work the way they are intended to

- Clean modern visual appearance which follows best practices

- Comprehensive baseball insights of major events that took place

### User stories

#### User

- As a new baseball fan I want a simple, beginner-friendly interface that allows me to explore player stats and learn about the game without feeling overwhelmed

- As a casual baseball fan I want to read about famous baseball events and moments so that I can relive key games and learn about the history of the sport

- As a dedicated fan I want to be able to find a website about the history of baseball

- As a baseball historian I want to compare historical team and player performances

#### Site owner

- As the operator of the site I want to be able to showcase the history of baseball to interested users

- As the the site owner I want to provide an enagaging user experience

- As the site owner I want to display important historical data from key events that took place

- As the site owner I want to promote the site to grow the user base

- As the site operator I want to continuously improve the platform

[Back to table of contents](#table-of-contents)

## Design

### Design choices

Since I'm a big baseball fan (Go Cubs, go!) I wanted to build a site which showcases the history of baseball in an easy to use way. The logo contains the name of the website. It has a minimalistic & clean interface with focus on the content. Every menu link clearly indicates what content the user can expect to navigate to. I used plenty of white space which draws the user to the key elements.

### Fonts

Fonts were used through import from https://fonts.google.com/. The chosen font for the body was _Roboto_ for its clarity and ease of reading. _Arial, sans-serif_ was chosen as the fallback font for all elements.

### Colors

I chose the color scheme of white for the font and blue for the background in the menu and the footer because it best represents my favorite team, the Chicago Cubs.

![Colors](assets/docs/menu-colors-fg-bg.png)

For the font-color used in the body I chose a classic dark charcoal with a classic white background.

![Colors](assets/docs/font-colors-fg-bg.png)

### Layout

I wanted to implement an intuitive design with a straightforward navigation. Therefore the website logo was placed in the top left corner and the navigation links in the top right corner. The header containing the logo and the menu was fixed to the top so that when a user scrolls the site he can easily access the menu to navigate to another page. The footer at the bottom contains the links to the social media accounts (each opens in a separate tab) on the left side. It also displays the website name and my name with the clarification of trademark, logo and brand names and their respective owners. The website contains 5 pages:

- Home with a background image of Wrigley Field underneath the header, an "About baseball" h1 element followed by 3 short paragraphs explaining the very basic rules of the game. After that is the "Famous former players" h2 element with the unordered list following containing 4 players with a brief explanation of their accomplishments. Following that is another h2 element containing the "Famous active players", again followed by an unordered list containing 4 players with a brief summary of their achievements.

- Early days with the background image of Wrigley Field underneath the header, a h1 element of "The early days of baseball" followed by 3 paragraphs about how the baseball rules were shaped in the early 19th century.

- Modern era with the background image of Wrigley Field underneath the header, a h1 element of "The modern era of baseball" followed by 8 paragraphs about how the game and its rules evolved starting from the beginning of the 20th century up till today.

- Milestones with the background image of Wrigley Field underneath the header, a h1 element of the "Key milestones" followed by an unordered list with 15 list items, each containing a significant historical moment in baseball history.

- Newsletter with the background image of Wrigley Field underneath the header, a h1 element of "Sign up for our newsletter" followed by an input form for the first name, last name and the email address. The user can submit their information by clicking on the "Sign up" submit button underneath.

### Wireframes

#### Homepage desktop wireframe

![Desktop wireframe](assets/docs/wireframe-desktop.png)

#### Homepage tablet wireframe

![Tablet wireframe](assets/docs/wireframe-tablet.png)

#### Homepage mobile wireframe

![iPhone wireframe](assets/docs/wireframe-iPhone.png)

[Back to table of contents](#table-of-contents)

## Features

The website contains 5 pages with 9 features in total.


<details>
    <summary>Logo and navigation</summary>  
    It is included on all 5 pages.<br> 
    The logo displays the name of the website & is a clickable link to the homepage which is just best practices.<br> 
    On the right there are five links to each of the pages: Home, Early Days, Modern era, Milestones and Newsletter so the user can easily navigate through.<br> 
    The current page the user is browsing at the moment is highlighted.<br>
    The logo and the menu are responsive, the page links become a burger menu when viewed on a mobile device.
    <img src="assets/docs/logo-navigation.png">
</details> 
<details>
    <summary>Footer</summary> 
    Appears on all 5 pages.<br>
    Divided by 2 divs with their class: social-links and footer-info<br>
    On the left are the social media links which open in a separate tab.<br>
    On the right is the website name together with my name and the information about ownership rights for trademark, logo and brand names.<br>
    It is responsive for all screen sizes, the social media links align over the website name and the accompanying information; both are horizontally centered.
    <br>
    <img src="assets/docs/footer.png">
</details>
<details>   
    <summary>Stadium image</summary>     
    Placed on the top of all pages<br>
    Displays "Welcome!" h2 on the top center with a plate image in the background welcoming the user to the website and the restaurant.<br> 
    It is responsive, the background image is resized and font-size reduced for smaller screens.<br>
    <img src="docs/features/feature-plate-image.jpg">
</details>
<details>
    <summary>Announcements</summary>
    Included on the Home page in the center of its section, under the plate image feature.<br> 
    Consists of two notifications displayed in the fieldsets for the user: the first one with its legend "!" an important urgent notice regarding a temporary               closure, and the other one is a special offer of the restaurant.<br> 
    It is responsive, text content for both notifications reduces its width and increases the height.<br>
    <img src="docs/features/feature-announcements.jpg">
</details>
<details>
    <summary>Opening hours</summary> 
    Included on the Home page in the center of its section, under the announcements feature.<br>
    Dispalys opening hours during weekdays and weekends.<br>
    It is responsive, reducing its font-size, weekend opening hours information slides under the weekdays opening hours for smaller screens.<br>
    <img src="docs/features/feature-opening-hours.jpg">
</details>
<details>
    <summary>Restaurant menu header and menu images</summary>
    Positioned on the top of the menu page.<br>
    Displays MENU h2 and three menu images presenting food and drink.<br>
    They are reponsive, the images wrap reverse for medium size screens so the third image from the left displayes on top of the two other images. For smaller screens the images are positioned from the top to the bottom. <br>
    <img src="docs/features/feature-restaurant-menu-header-and-menu-images.jpg">
</details>
<details>    
    <summary>Food Menu and Drinks Menu</summary>
    Can be found on the menu page below the restaurant menu header and menu images feature.<br> 
    Lists the food and drinks offer and the prices of the restaurant.<br>
    They are responsive, Drinks Menu slides under Food Menu for smaller screens.<br>
    <img src="docs/features/feature-food-menu-and-drinks-menu.jpg">
</details>
<details>
    <summary>Our Place</summary> 
    First section of the About us page, appears under the logo and navigation bar feature.<br>
    Consists of a text describing what is the place and an image of restaurant's interior.<br>
    They are responsive, the text content reduces its width and increases the height, and the image slides under the text for smaller screens.<br>
    <img src="docs/features/feature-our-place.jpg">
</details>
<details> 
    <summary>Our Chef</summary>
    Second section of the About us page, appears under the our place feature.<br>
    Consists of a text describing who is the chef and his image.<br>
    They are responsive, the text content reduces its width and increases the height, and the image slides above the text for smaller screens.<br>
    <img src="docs/features/feature-our-chef.jpg">
</details>
<details>  
    <summary>Our Guests</summary>
    Third section of the About us page, appears under the our chef feature.<br>
    Consists of a text with other guests reviews of the restaurant. <br>
    It is responsive, the text content reduces its width and increases the height.<br>
    <img src="docs/features/feature-our-guests.jpg">
</details>
<details>
    <summary>Contact form</summary>
    Placed on left side in the center of the Contact page.<br>
    Includes a form with name, email, and phone inputs, a textarea, and a submit button for the user.<br>
    The form is responsive, adjusting the size to the viewport and moves above the map for medium size screens.<br>
    <img src="docs/features/feature-contact-form.jpg">
</details>