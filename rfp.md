# RFP - Habit Reminder

## Statement Of Purpose

Change your habits and change your life.... 

1. The habit remainder is an app used to know either we did a habit or not. 
1. The progress of habits can be monitored and viewed using day to day completion rates, streaks and detailed statistics.
1. This app used to customize the habits on particular day that means we can add or delete the habits.
 
 ## Project Vision
 
 We could like to create a progerssive web application that can be played in any mobile device. <br>
 The app would encourage it uses to complete a 'Daily Habit' by giving specefic task per day. <br>
 This app has a number of great features which makes it ideal for keeping track of habits and routines.
 
 This app has a number of great features which makes it ideal for keeping track of habits and routines.
 Used together, you’ll be able to develop healthy habits with ease. If you’re falling behind, the app will send you a reminder, and keep you on target.
 
If you’re looking for inspiration, the application comes with over pre-designed habits to get you started. One of the most appealing things is the beautifully designed and eye catching interface.

The app is quick and easy to use, so you’ll be able to start developing great habits right away. If you plan to complete a set number of tasks for a specific date, the app calculates if you’re on track to complete it on time, enabling you to tailor your habits around your goals.

When day starts...

1. User gets some pre-defined habits where he gets remainder to complete it.
2. Some habits can be customized on date which reminds user to complete within the time.
3. The completation of habits gives credit to the user which motivates him to be healthy with ease.
 
 ## Meet Our Team
 
  - **Abhilash Dhumala** - Product Advisor<br> 
  - **Arnav Akula** - Product Owner <br> 
  - **Naveen Tanuku** - Decision Maker<br>
  - **Sanjay Saripalli** - Requirment Specialist <br>
  
  
 ## Functional Requirements
 
 Create a progressive web app with authentication and authorization.
 1. Administrator(access to all information including app settings)
 2. User(access to their content)
 3. Head and Footer
 4. View Habits 

### Authentication:
The authenication is only for the Administrator, who has control over the data in the app. The authentication page must contain the following:

1. ***username***, ***password*** fields
2. A ***Captcha*** field to verify it's a real person and not a bot.
3. A ***submit*** button to validate the credentials provided by the admin.
4. If the details entered are **correct**, the page is redirected to **admin panel**.
5. If the details entered are **incorrect**, an error message is displayed stating **"Invalid credentials. Please contact the administrator"**

### Header and Footer:

1. The screen has logo on the top-left side
2. The right-top side of the screen is with account icon which contains profile settings and logout.
3. The footer has add a joke icon which is used to add a habit to the account.

### View Habits:

1. User has atleast one habit which can be added after profile creation
2. The habit can be viewed by clicking on the habit name
3. User can check the habits and check in the box if the habit is completed.
 
 ## Expected Entities:

 ### User
     - Email
     - Password
     - CreatedOn
     - Gender
     - UserID -> PrimaryKey
     - UserName

### Habits
    - HabitId -> PrimaryKey
    - UserName
    - Image
    - Description
    - Points Attained
 
 ## Screen Flow:
 
 Home Screen: Consists of a header with login button, a footer and a box that displays habit of the day, and an image and a button that directs to the Habit details screen.</br>
 <br>Login page: This a admin login page, from where admin gets access to add, remove or update the data.</br>
 <br>Habit details screen: This screen displays all the details of the habit to complete the habit like an image and description of what to do. If the user wants to push his limits he/she can customize the habit. We have a button that redirects to the Habit Customization Screen</br>
 <br>Habit Customization Screen: This screen allows the user to customize the habits based on his/her interest.</br>
 
 ## Tech Stack
 
Scripting Language : Python</br>
Query Language : SQL</br>
Backend Framework : Django</br>
Frontend Library/ Framework : React, Bootstrap</br>

## Entity-Relationship diagram:



## Themes & Colors:

Application carries a theme of white for the background and Green for headers, footers, buttons and menues as green mostly uesd to represent nature and health.

## Device Support:

The App must work on:
- an IPhone SE
- an Android Device
- a laptop Computer
- an iPad

## Font size:
The Font preference is between 12-14px, which is easier to read.

## Bidder Qualifications

- Product based application which can maintain self.
- Ready to use public apis with less cost.
- Make sure to develop other features if extension required.
- Must complete within 45 working days and 5 working days for acceptance testing and 3 days for prod release and fixes.
- Maximum of 2 developers.

## Performance Metrics

- Responsive application in all kinds of devices. 
- Eg: Android devices all screen sizes, iOS devices, and Desktop and laptops screens.
- Page load max weight time for home screen is 3 seconds - 5 seconds
- Home page load weight is less than 100kb.


## Schedule:

- 18-Aug-2021 to 28-Nov-2021 Requirement Gathering, Specifications and Mockup designs.
- 12-jan-2022 to 24-Mar-2022 Development,
- 24-Mar-2022 to 4-Apr-2022 Testing  
- 4-Apr-2022 to 7-Apr-2022 Release.

## Point Of Contact:
Please feel free to reach us for any queries and find below contact details,
 - **Abhilash Dhumala** - Product Advisor  - S542295@nwmissouri.edu <br> 
  - **Arnav Akula** - Product Owner - S542308@nwmissouri.edu <br> 
  - **Naveen Tanuku** - Decision Maker - S542000@nwmissouri.edu <br>
  - **Sanjay Saripalli** - Requirment Specialist - S541669@nwmissouri.edu <br>

## Source:

<https://github.com/denisecase/rfp-hunt/edit/master/rfp-hunt.md>
