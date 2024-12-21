Country Quiz: A Knowledge-Testing Android Application

This project involves developing a feature-rich Android application, Country Quiz, that tests users' knowledge of countries, their continents, and neighboring countries. Designed for flexibility and interactivity, the app uses fragments, SQLite database, CSV data, and Android's modern development tools to ensure a seamless user experience.

Key Features

Quiz Initialization: Reads country and continent data from a CSV file and stores it in an SQLite database. Uses AsyncTask for efficient IO operations.
Dynamic Quiz Generation: Randomly selects six countries for the quiz and generates three options per question, including the correct continent and two distractors.
Interactive UI: Allows users to answer questions using radio buttons and swipe gestures for navigation.
Score Tracking: Displays results at the end of each quiz and stores quiz history, including scores and dates, in the SQLite database.
State Management: Saves quiz progress, enabling users to continue from where they left off if interrupted by another app.
Past Results: Displays a list of previous quiz scores and dates from the SQLite database.
Optional Navigation Drawer: Offers enhanced navigation within the app.
Additional Features for Honors Teams

Neighboring Countries Quiz: Includes an advanced section where users answer questions about neighboring countries, incorporating a "No neighbors" option for countries without borders.
Dual Questions Per Screen: Combines continent and neighboring country questions on the same screen for efficiency.
Enhanced Database Schema: Handles varying numbers of neighboring countries using the provided CSV file.
Tech Stack

Development Tools: Android Studio Hedgehog, Java.
Database: SQLite.
UI Components: Fragments, swiping gestures, radio buttons, and ConstraintLayout.
Additional Notes
The app prioritizes modular design, optimized IO operations, and clean Java coding practices with comprehensive documentation. Testing is performed on a Pixel 7 (API 32) emulator for stability and performance.
