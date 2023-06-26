<h2 align="center">NUS Orbital 2023 - Milestone 2</h2>

### **Team Name:**
TaskMaster

### **Proposed Level of Achievement:**
Project Apollo

## **Motivation**
Many students uses multiple calendars (Eg. Google Calendars, NUSMods, Outlook etc) to schedule their daily routine. Many find it inconvenient in planning their daily task when using multiple platform. As such, why not create an app to sync multiple calendar together while integrating to-do list features to organize day-to-day tasks. This increases the productivity efficiency which helps get things done and helps to plan ahead for future events.

Also, imagine having a personal assistant that can anticipate your needs and help you manage your time more efficiently. By integrating AI technology into a productivity app, we can offer users a level of convenience and automation. By learning from user behaviour, we can provide personalized suggestions for prioritizing tasks, setting reminders, and scheduling events. With the power of AI, we will be able to adapt to the unique needs and preferences of each user, providing a truly personalized productivity experience.

## **Aim**
We hope to create a centralized productivity app integrating calendar and to-do list features for students to schedule their day-to-day activities and to manage their time more efficiently. We also aim to use AI to analyse user behaviour to provide a more personalized user experience and improve the overall quality of life.

## **User Stories**
1.	As a student who uses multiple calendars, I want to be able to integrate both my personal calendar and my school calendar together.

2.	As a student who often overlap events on the same day, I want to be able to organize my daily routines so that I can better plan my days.

3.	As a student who is forgetful, I want to be able to keep track and be reminded of my day-to-day activities

4.	As a student who like to find free time in my schedule, I want to be able to find out which day I am available just by asking someone, like a personal secretary.

5.	As an administrator, I want everyone to have their own accounts so that they can sync their schedule and task across multiple devices to have a more personalized experience.

## **Features**
The ***Integration of Calendars*** provides a centralised place for students to manage their schedules and combined the different calendars they have.

A ***To-Do List*** provides students an option to manage their tasks and plan their daily schedules ahead of time as well as setting reminders. A ***Pomodoro Timer*** option to help students to stay on track for their task and get it done by a certain deadline.

Introduction to ***AI Technology*** which predicts students' schedules and suggest task to help them plan their daily routines better.

### **To-Do List**
To allow users to manage their tasks and plan their daily schedules.

Equipped with the following functions:

#### **Deadlines**  
To allow users to set deadlines on their To-Do List, so that they can keep track of all their deadlines in one place.

#### **Reminders**  
To remind users of their day to day tasks and events planned. Users will be able to receive notifications from setting reminders in their To-Do List.

#### **Task Prioritization**  
To give priority to different tasks, so that users can differentiate the more important tasks first.  
Priority levels such as `Low, Moderate, High` will be used and can be assigned to each task.

#### **Pomodoro Timer**  
To help users concentrate on a specific task and allow them to hit deadlines quickly to save time. Users will be able to customize the duration of the timer as well as the breaks in between. 

### **Integrated Calendars**
By combining different calendars (Google Calendars, Outlook, NUSMods etc) into one, this allows users to integrate their timetable into their calendars. This makes it easier for users to plan and manange their time more efficiently.  
  
Users will be able to keep track of their task on their calendars as well, making it a one stop place to handle and view their schedules.

### **Personalised Experience (Using AI)**
To provide users with suggested tasks and events based on their past task logs. It will identify the users' behavioural pattern and aid them in planning their schedules. This will help to make their user experience more personalised. 

## **Timeline**
Features to be completed by the mid of June:
1. Integrating multiple calendars from different platforms (Google Calendars, Outlook, NUSMods)
    * Allow users to sync different platforms calendars in one app
    * Display the schedule in different formats
2. To-do list (Integration with phone reminder to push notifications)
    * Allow users to prioritise which task is important
    * Allow users to add tags to categorize their tasks
    * Allow users to set reminders on individual task
3. Mechanism to collect datasets for analysis
    * To help understand user’s routines and recommend task prior to the event.
      * E.g. Birthday party need to buy a gift beforehand
      * E.g. Recurring schedules (Run once a week)  

Features to be completed by the mid of July:
1. Pomodoro Timer (Integrate with To-Do List to get things done) 
2. Providing recommendations with machine learning 
    * E.g. Recognising recurring schedules
    * E.g. Suggesting task based on past task logs
    * E.g. Recommending task based off users' event
3. Login System (Login using NUS/Google Accounts)

## **Current Progress**
For Milestone 2, we have created a to-do list tab where users will be able to create and delete tasks as well as set a deadline. All of these data are linked to our backend database on Firebase. There is also the Calendar tab where users will be able to view which date they have set a task for. We have also implemented an authentication feature, where users will be able to register an account and log in with it. The account has its own unique user id where its todos are unique to each account where all of these data are stored in Firebase. We have also implemented a forget password feature where it will send an email to the user to change their password. We are still trying to figure out how to allow sign-in with the user's Google account, as well as integrating the calendars from other platforms. More features will be added by Milestone 3, such as prioritisation, reminders, colour tags, as well as displaying todos within the same month at the Calendar tab.

Technical proof of concept (ios may have issue): https://expo.dev/@felixchanyy/TaskMaster?serviceType=classic&distribution=expo-go
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/83b02995-1929-43c6-a7ae-5c633bc7d189" width="300" height="700">
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/418f2c79-cc2c-4043-9a97-a33ef31e193d" width="300" height="700">
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/117510b4-0395-49a4-a9d7-44dc53bbc6b8" width="300" height="700">
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/5039115c-fec2-4208-a079-81358649a011" width="300" height="700">
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/92bf43aa-a35c-4b14-b0a6-f2af9bfe29f8" width="300" height="700">
<img src= "https://github.com/jasperng-nus/orbitalsubmissions/assets/111300022/030d6a19-39f3-4ba5-bba6-c3ac6276bb62" width="300" height="700">







