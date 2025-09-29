# To-Do List App

## Project Description
This project is about building a to-do list app where users can create, mark as complete, and even delete tasks if necessary.  The app will store tasks on the phone, display them in a list, and allow users to edit tasks respectively.

## Problem Addressing
Everyone has daily tasks, but keeping track of them on paper or in your head isn’t the way to go. This app provides a way to organize tasks and boost productivity. It’s simple, lightweight, and will natively have an offline capability.

## Platform
Android  
Minimum SDK of Android 8.0

## Front/Back End Support
Frontend: XML for UI development & Activities/Fragments to control the screens  
Backend: Room for data manipulation; possibly LiveData depending on how the app evolves

## Functionality
Add a Task: User types a new task into a text box and saves it.  
View Tasks: Tasks appear in a scrollable list.  
Edit Task: User taps a task to update its text.  
Delete Task: Swipe left/right and confirm to delete a task.  
Mark Complete: Checkbox to mark a task as done.  
Tasks will remain if the app is closed and reopened.  
Again, depending on app evolution, additional functions may be added such as due dates and notifications

## Design (Wireframes)
-----------------------------------
|   My To-Do List                 |
-----------------------------------
[ ] Get gas  
[ ] Stop at the ATM on the way home  
[X] Finish project outline
-----------------------------------

-----------------------------------
|   Add Task                      |
-----------------------------------
Task Name: [__User Input__]  
[ Save ]     [ Cancel ]
-----------------------------------

<img width="1050" height="865" alt="image" src="https://github.com/user-attachments/assets/9e5dd916-fc8e-4b90-a60a-cb81f6e6ec61" />
![1000076700](https://github.com/user-attachments/assets/c62d4463-9d33-435e-8f8e-1b465334bbe5)

# Updated/Refined Outline

## Project Description
This project focuses on building a simple but effective to-do list app for Android. The app allows users to create, mark as complete, edit, and delete tasks as needed, with everything stored directly on the device so tasks are available even after closing and reopening the app. The goal is to provide something lightweight, reliable, and offline-first, while leaving the door open to the way forward such as the implementation of Firebase.

## Problem Addressing
Everyone has daily responsibilities, and managing them in your head or as hand-written notes often leads to forgotten tasks and disorganization. This app addresses that problem by providing a straightforward digital solution for organizing and completing tasks. Its simplicity keeps it approachable, while its built-in persistence makes it more dependable than memory alone. At the same time, its design is flexible enough to expand into more advanced territory such as reminders or multi-device syncing.

## Platform
The app will be built natively for Android using Android Studio as the development environment. It will target a minimum SDK of Android 8.0 (Oreo) to ensure compatibility across a wide range of devices. Development and testing will be carried out both on the built-in Android emulator and physical devices to ensure stability.

## Front/Back End Support
On the front end, XML will be used for the layout design, paired with Activities and possibly Fragments to control the screens. A RecyclerView will display tasks in a clean, scrollable list, while a floating action button provides a quick way to add new tasks. On the back end, the app will rely on Room for database persistence, which will allow tasks to remain even after the app is closed. The architecture will also use ViewModels and LiveData to help keep data updated. As the app evolves, optional cloud services such as Firebase could be introduced to handle syncing, authentication, and analytics.

## Functionality
The core functionality of the app is centered around managing tasks. Users will be able to add new tasks through a simple input form, view them in a scrollable list, edit their details by tapping on them, and delete them by swiping left or right with a confirmation step to prevent mistakes. Each task can also be marked as complete with a checkbox. Importantly, tasks are persistent, meaning they remain saved and visible after closing and reopening the app. In future versions, new features such as due dates, reminders, or notifications may be layered in without disrupting the simplicity.
