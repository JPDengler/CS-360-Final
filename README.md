# CS-360-Final

## Project Overview

### App Summary
The "Nuoro" app is designed to help users track their weight over time, set personal weight goals, and receive SMS notifications to stay motivated. This application was developed as part of a course project for CS-360: Mobile Architect & Programming. The primary goal of the app is to offer a simple, user-centered tool for weight management that integrates essential features like goal setting, data entry, and notifications.

### User-Centered Design
The app features several screens, each tailored to support user needs:
- **Login Screen**: Users can create an account and log in securely, with fields for username and password.
- **Main Dashboard**: This screen displays the user's goal weight, allows data entry for date and weight, and offers options to set a new goal weight or clear existing data.
- **Set Goal Weight Screen**: A straightforward interface for users to input their target weight.
- **SMS Permission Screen**: Users can easily grant permission for SMS notifications, which are used to encourage them to meet their weight goals.

The UI design prioritizes simplicity and ease of use. The clean layout, intuitive buttons, and clear feedback (e.g., success messages after data actions) ensure that users can navigate the app effortlessly.

### Coding Approach
The app was developed using a modular approach, focusing on one feature at a time. I implemented a clear structure, starting with setting up the necessary user interfaces, followed by integrating back-end logic for data management and SMS notifications. This iterative development process allowed me to test and refine each feature before moving on to the next, ensuring stability and performance.

### Testing and Validation
Rigorous testing was performed throughout the development process. Each screen and feature was tested individually to confirm that it worked as intended, and end-to-end testing ensured that the entire app functioned correctly. This testing revealed several areas for improvement, such as refining the SMS notification flow and ensuring data persistence, which were addressed before finalizing the app.

### Overcoming Challenges
One of the primary challenges during development was integrating the SMS notification system without disrupting other app functionalities. I had to innovate by researching alternative approaches to Android's permission system and ensuring that notifications were sent only when the user had explicitly granted permission. This challenge helped me deepen my understanding of Android's security and permissions architecture.

### Success and Knowledge Demonstration
I was particularly successful in implementing the app's data management and user interaction components. Although the current version of the app includes create, read, and delete (CRD) functionalities, I plan to implement the edit function in the future to complete the full CRUD capability. The seamless goal-setting feature and the effective use of notifications highlight my ability to create user-centered applications that meet real-world needs.
