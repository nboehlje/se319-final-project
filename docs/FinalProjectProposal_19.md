SE 3190: Construction of User Interfaces  
Fall 2024  
Final Project Proposal

# SE 3190 Final Project Proposal: Team #19  <!-- omit from toc --> 

- Nathanial Boehlje - nboehlje@iastate.edu
- Nathan Willimack - nawilli@iastate.edu
- 11/17/2024

## Table of Contents <!-- omit from toc --> 
- [1. Description](#1-description)
  - [1.1. Introduction](#11-introduction)
  - [1.2. Objectives](#12-objectives)
- [2. User Experience](#2-user-experience)
  - [2.1. Visual Representations](#21-visual-representations)
  - [2.2. View Descriptions](#22-view-descriptions)
- [3. File Structure and Management](#3-file-structure-and-management)
  - [File Descriptions](#file-descriptions)
    - [`HTML` Files](#html-files)
    - [`CSS` Files](#css-files)
    - [`JSON`](#json)
    - [`JavaScript`, `js` Files](#javascript-js-files)
    - [`JSX` Files](#jsx-files)
  - [Data Flow and Structure](#data-flow-and-structure)
- [4. Data sources and Management](#4-data-sources-and-management)
  - [Data Sources](#data-sources)
  - [Data Format and Processing](#data-format-and-processing)
  - [Data Flow and Transformation](#data-flow-and-transformation)
- [5. Final Comments](#5-final-comments)


## 1. Description

### 1.1. Introduction

Trying to keep you mind stress-free while waiting for something personally significant to occur can be challenging, sometimes the most effective way to reduce stress is by engaging in a healthy distraction.

Simple, browser-based games can be an enjoyable way to spend time while sitting in a waiting room or attempting to clear you nerves before an important presentation. For example, waiting at the doctor's office or taking a small break right before you deliver a stressful update on your project at work. 

### 1.2. Objectives

1. To develop an entertaining browser game that will provide a small (non-addictive) distraction to players. I.e. provide a small dose of joy to ease the mind before a potentially stressful event.

2. The game should be interactive and simple. It should also support player personalization and recognition of achievement.

3. Develop an interactive space travel game where the user provides input through their keyboard to direct a spaceship through a field of asteroids.
    1. Users will navigate their ship by pressing the right and left arrow keys.
    2. Users can shoot at the asteroids to destroy them, by pressing the space key.
    3. The game ends when the ship is struck by an asteroid OR 5 minutes has elapsed.

4. Develop personalized player experience.
    1. Allow users to create a custom user profile and upload a photo of themselves on a "profile" page.
    2. The users will be able to enter a username, upload a photo, and register their email for optional leaderboard updates. 

5. Develop a leader-board page where users can view their 10 highest scores. (Recognition of player achievement)
    1. The leader-board will be interactive. Users will not have to reload the page to see updated scores. 
   
6. Develop a live-chat experience where players can send messages in real-time to one another. 
   1. A user can initiate a chat session by entering a username to deliver the chat message. 
   2. A user can initiate a chat session by selecting someone on the leaderboard to chat with.
   3. The user receiving the message can accept or dismiss the incoming chat request.   

7. Develop 4 web pages:
    1. A main/central page with information about the game and links to the 3 other pages.
    2. The game surface page, where the user plays the game. 
    3. A profile page where the user can view and edit their profile information.
    4. A leaderboard page where users can view their top 10 highest scores. 

## 2. User Experience 

### 2.1. Visual Representations
The game will be a "space invaders" style shooter where the user directs their ship with the right and left arrow keys, clearing the asteroids from the ship's path.

### 2.2. View Descriptions

## 3. File Structure and Management

### File Descriptions 

#### `HTML` Files

Hypertext Markup Language files are used for rendering visual content within a web browser. Typically each HTML file represents one web "page", a scrollable view with text images or other visual content such as 3-D graphics. 

HTML markup is composed of building blocks called elements.  

#### `CSS` Files

Cascading Style Sheets are used to impart visual styles to HTML elements. For example placing a boarder around a block of text, or changing the background color of a HTML element. 

#### `JSON`  

Javascript Object Notation is simply a textual data storage format. It uses special sequences of UTF-8 encoded characters to define data structures. E.g., `"numbers": [ 1, 2, 3 ]` represents an array of integers called `numbers`. 

#### `JavaScript`, `js` Files 

JavaScript is a programming language that can be embedded inside HTML files to give "behavior" to the web page. For example JavaScript could be used to change the color of a button when it is pressed by the user. Another use case is making network requests to get some data from a server without requiring the user to reload the page. 

#### `JSX` Files

JSX is a file format for using HTML strings within a JavaScript file, without requiring escape sequences and messy string interpolation. It is used by the React framework for creating components, which are basically independant UI objects. 

### Data Flow and Structure



## 4. Data sources and Management 

### Data Sources 
### Data Format and Processing 
### Data Flow and Transformation

We’re considering expanding this project into a platform with multiple games that users can choose from. Players would be able to log in, track their progress, and view leaderboards to see how they rank against others. It would also save their game data, so they can pick up where they left off and compare their scores with friends.

Additionally, an interactive 'real-time' multiplayer version of the game could be developed, using WebSockets.

## 5. Final Comments

We believe this project will be an excellent opportunity to practice both front-end web development and game development. Our goal is to deliver a polished, enjoyable game that meets the requirements for this course while challenging ourselves to explore new technologies and game mechanics.