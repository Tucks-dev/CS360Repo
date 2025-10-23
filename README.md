1. App Requirements and Goals

The goal of the project was to create a functional mobile application where users can manage inventory items, log in securely, and send SMS-based notifications for important updates. The app focuses on providing an easy-to-use interface where users have liberty to insert, read, and delete inventory data with the capability to manage permissions for text message notifications.

This application was developed to address the user need of having a simple and organized way of tracking things and receiving real-time alerts in a neat and easy-to-use mobile app.

2. Screens and Features Supporting User Needs

The application has three primary screens:

Login Screen:
Allow users to log in using a username and password or sign up. Returning users can login, while new users can sign up directly from the same page. 

Inventory Screen:
Displays items in a grid-type table with buttons to add new ones or delete existing ones. This screen makes it simple for users to view information at a glance and perform actions quickly.

SMS Notifications Screen:
Prompts the user to grant or deny sending SMS notifications. Once permission has been granted, users can send test messages simulating notification actions. A "Back to Inventory" button allows easy navigation to the inventory screen.

Its UI is designed with users in mind with large buttons, readable text, and logical spacing. The color scheme throughout the app is consistent, with visual flow and accessibility ensured. These design principles ensure that the interface is usable, even for first-time users.

3. Coding Approach and Techniques

The coding was completed in a well-structured, modular manner. Each screen was controlled by its own Java class (MainActivity, DataActivity, and SmsActivity), making the code easy to maintain and debug.

Some of the key techniques that were implemented included:

Event-driven programming for button clicks and user interactions.

Input validation to prevent errors when adding or editing inventory information.

Dynamic UI updates that refresh displayed information when new information is inserted.

Intent-based navigation for moving smoothly between activities.

These practices ensured that each piece worked on its own but also integrated smoothly into an end-to-end user experience. The same practices can be applied to future projects to keep code in a structured, readable, and scalable manner.

4. Testing and Debugging

Testing was conducted on the Android Emulator in Android Studio. The app was tested for usability, navigation, and proper SMS permission handling.

Test scenarios included:

Logging in with new and existing users.

Insertion and removal of products into the inventory grid.

Sending SMS after allowing permission.

Testing whether the app still works as intended when the SMS permission is denied.

This testing rendered the app stable in all user situations possible. It revealed small logic issues during development (such as how to handle SMS permission denials), which were resolved before completion. Testing guaranteed that the app could gracefully handle permission status changes and user input without crashing.

5. Innovation and Problem Solving

A significant development challenge was how to make the SMS permission system dynamic and secure. Early app versions did not handle denial responses graciously, and the app could break. The final version addresses this with explicit user prompts and conditional checks for permission status prior to attempting to send any message.

In addition, the inclusion of a "Back to Inventory" navigation button improved the app's flow and made sure that the users were not stuck in the notification page. These small design decisions added to the overall usability and demonstrated creative problem-solving.

6. Areas of Success

One of the strongest points of the app is the SMS notification feature that appropriately handles real-world scenarios of permission granting and denial. The permission logic, user feedback via Toast messages, and screen navigation demonstrate technical skill and regard for user experience.

Another area of success was a tidy, user-focused UI. By paying attention to clarity, whitespace, and logical structure, the app is simple to use in a way that exactly aligns with user needs and Android design guidelines. 

Summary

The Inventory Management and Notification App successfully integrates user experience, SMS functionality, and structured navigation all into a single mobile application. Everything, from the initial login screen to the real-time SMS notifications, was developed with the user in mind first. This project demonstrates the ability to organize, design, develop, and test a complete Android application using modern development best practices and user experience-centered design principles.
