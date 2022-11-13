# Milestone 1 Recipes

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)

## Overview

### Description

Recipies is an app that has hundreds of recipes from many different categories that food enthusiasts can choose from. 

### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** 
Fitness Social media mobile application
- **Mobile:**
The app focuses on fitness tracking which could be done using a mobile device or a wearable due to the portability constraints associated with fitness.
- **Story:**
The app would encourage fitness amongst friends and peer in a closed social circle. The users would be motivated by friends to up their fitness and take part in challenges to earn their place in the leaderboard.
- **Market:**
The app can be used by anyone interested in fitness and well being.
- **Habit:**
It forms an habit around fitness and would be used by user daily to track and improve fitness.
- **Scope:**
There are challenges as we would be using GPS like features to track the walks/runs, also we would be building REST API's whice time frame.

## Product Spec

### 1. User Features (Required and Optional)

**Required Features**

[X] Log In/Sign up 
[X] Tracking your run/workout
[X] Workout suggestion
[] Workout Dashboard
[] Streaks
[] Ability to add friends
[] Mainting Profile

**Stretch Features**

* Sharing image and updates amongst friends
* Calorie tracker for food
* Interacting with users

### 2. Screen Archetypes

- Log In/Sign up
  - Allow signup using google ID
  - Database design
  - Rest endpoint to create the entry in DB
- Main Screen
  - Workout
    - UI to start and stop runs
    - Use the GPS to track the run
    - Rest API's to save the data to the associated user
  - Followers
    - Ability to add users as friends and see the friends stat 
  - Dashboard
    - Ability to see your stats  
  - Profile
    - Ability to update the profile details with workout preferences and other details.  

### 3. Navigation

Login screen to Main Screen
**Tab Navigation** (Tab to Screen)

* Workout - Has workout details, like start runs, etc
* Followers - Has friends list and ability to add friends
* Dashboard - Has user stat/workout details
* Profile - User profile screen

**Flow Navigation** (Screen to Screen)

- Login Screen
  - Navigate to Main screen on successful login
- Main Screen
  - Can Navigate between tabs (Workout, Followers, Dashboard, and Profile)

## Wireframes

<img src="https://github.com/PranaMohanty13/GetFit/blob/main/Befit_part2_walkthrough.gif">

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

# Activity 1:
https://hackmd.io/s/H1-2wfIEs
