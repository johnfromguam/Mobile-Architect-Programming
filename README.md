# Mobile-Architect-Programming
# Event Calendar Mobile Application
## Overview
The event calendar Mobile Application is a Android app developed using Kotlin in Android Studio. The purpose of this application is to provide users with a simple and efficient way to create, store, and manage personal events. The app uses a local SQLite database to ensure events are saved persistently across sessions. This project demonstrates core mobile development principles including UI design, local data storage, runtime permissions handling, and structured application architecture.
---

## Problem Statement
Many users need a lightweight solution to track events without relying on complex third-party calendar systems. This application was designed to:
- Allow users to create and store events
- Display events in an organized list
- Maintain persistent event data
- Provide an intuitivee and user-friendly interface
The goal was to build a functional mobile app that meets user needs while following best practices in Android development.

---

## Features
- Add new events through a structured input form
- Store events in a local SQLite database
- Display saved events in a list view
- Persistent data storage across app restarts
- Runtime permission handling (SMS permission if applicable per rubric requirements)

---

## User Interface Design
The UI was designed with simplicity and usability in mind. Key design considerations included:
- Clearly labeled input fields
- Logical layout flow
- Minimal required inputs to reduce friction
- Familiar list-based event display pattern
- Clean, uncluttered screen design
The design prioritizes user-centered principles by ensuring ease of navigation and quick interaction.

---

## Development Approach
The app was developed incrementally using a modular approach:
1. Designed and implemented the UI layout.
2. Integrated database functionality using a dedicated database helper class.
3. Connected UI components to database operations.
4. Implemented runtime permissions.
5. Tested functionality in the Android emulator.

Key strategies used:
- Separation of concerns (UI vs. database logic)
- Step-by-step debugging
- Testing small componenets before full integration
- Iteative refinement based on errors and rubric feedback

---

# Testing Process

Testing included:
- Verifying successful event insertion into the database
- confirming persistent storage after app restart
- Ensuring UI responsiveness
- Validating permission handling behavior

Testing revealed integration issues during development, which were resolved through structured debugging and incremental testing. This process reinforced the importance of validation in mobile development.

---

## Challenges and Solutions

One major challenge was ensuring smooth interaction between the UI and the SQLite database. Although the app compiled successfully, some data operations initially did not behave as expected. By isolating database methods and testing them independently, I was able to resolve these issues.  Another challenge involved implementing runtime permissions correctly while maintaining application stability. Addressing these challenges strengthened my understanding of Android lifecycle managemenet and application architecture.

---

## Demonstrated Skills
This project demonstrates:
-Kotlin programming
-Android Studio development
-SQLite database integration
-Runtime permissions handling
-User-centered UI design
-Debugging and problem-solving
-Incremental software development practices

---

## How to Run the Application
1. Clone this repository
2. Open the project in Android Studio
3. Allow Gradle to sync
4. Run the application on an Android emulator or physical device
5. Add and manage events within the app interface.

---

## Portfolio Reflection
The Event Calendar App demonstrates my ability to build a functional mobile application from initial planning through deployment. It highlights my ability to integrate persistent data storage, design user-centered interfaces, and troubleshoot development challenges efficiently. This project reflects growth in mobile application architecture, structured coding, practices, and real-world problem-solving within Android development

