## BudgetEase – Personal Budget Tracker App

BudgetEase is a fully functional personal budgeting app developed in Kotlin using Android Studio. This app was created as part of our Part 2 – App Prototype Development for our Portfolio of Evidence (POE). We're proud to share that this is not just a prototype, but a working app that runs smoothly on Android devices.
As a group, we went beyond the initial assignment requirements by adding extra functions and databases to improve the overall performance and user experience. Every feature was carefully implemented to ensure it aligns with real-world budgeting needs and works effectively across a range of Android phones.

The app starts with a secure login screen where users enter their username and password to access their personalized budget environment. After logging in, users are welcomed with a clean and user-friendly dashboard, allowing them to:

View recent transactions
Add new expenses or income
Create and manage custom categories
Set monthly budget goals (minimum and maximum)
Each expense entry supports:
Amount input
Date selection (using a built-in date picker)
Description field
Category selection
Optional receipt photo upload

**All user data is stored locally using RoomDB, ensuring full functionality even when the app is offline. To enhance the app's functionality and scalability, we also created additional databases and modules that support smooth data handling and better performance.**

We also added advanced reporting features, allowing users to:
View total expenses over any selected time period
Access attached receipt images directly from the report view
Analyze spending trends per category, helping users make smarter financial decisions
Our focus was not only on features but also on robustness and usability. We handled unexpected inputs gracefully—when a required field is left empty or the wrong input type is used, the app responds with helpful prompts instead of crashing. We used logging and debugging techniques to maintain app stability and trace errors efficiently during development.
Throughout the development process, we practiced proper version control by using GitHub. We committed code frequently and integrated GitHub Actions for automated builds and tests on every push. This ensured our app was always in a working state, regardless of the device or environment.

Our code is:
Clean and well-commented
Structured with good use of layouts, intents, and activities
Demonstrates our knowledge of Android development principles including data persistence, UI/UX design, and user input validation

