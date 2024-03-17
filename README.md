# JamesElias_hw5TH

Overview
------------------------------------------------------------------------------------------------------------------------

This is a basic JavaScript, HTML, and CSS quiz application. Users of the program can participate in a multiple-choice quiz covering a variety of subjects. It has functions like a scoring system, timer, and dynamic question rendering.

How-To:
------------------------------------------------------------------------------------------------------------------------

1. Access the index.html file using a web browser.
2. Initiate the quiz by clicking the "Start Quiz" button.
3. Carefully read each question and choose your answer.
4. Remember, once you select an answer, it's final.
5. Finish all questions within the specified time limit.
6. Upon completing all questions, your score will be revealed.

Structure
------------------------------------------------------------------------------------------------------------------------

There are three primary files in the application:

style.css: This file houses the quiz app's CSS styling. It specifies how certain elements, like text formatting, buttons, containers, and animations, should look.

The JavaScript functionality for the quiz app is contained in the file quizApp.js. It manages all user interactions, including initiating the test, choosing alternatives, figuring out scores, showing outcomes, and setting the timer.

index.html: The web page's structure is contained in this file. It outlines the quiz app's design, including the questions, options, timer, quiz box, start button, and result box, among other components.

The array of quiz questions, each with a question, alternatives, and the right answer, is also stored in a questions.js file.

Implementation
------------------------------------------------------------------------------------------------------------------------

index.html: 
The index.html initializes a quiz app structure with questions, a timer, directions, and result display, controlled by linked JavaScript files. Users can navigate questions, view scores, and interact with dynamic content loaded from separate JavaScript files.

style.css: 
The style.css file defines the visual aspects of the quiz app, covering layout, colors, typography, and interactive elements using CSS properties and selectors, ensuring a cohesive and visually appealing interface.

quizApp.js:
The quizApp.js file manages quiz functions such as start/restart, user answers, score updates, and timers, dynamically interacting with HTML to display questions, options, and outcomes while incorporating time management and progress tracking.

questions.js:
The questions.js file holds an array of objects representing quiz questions, options, and correct answers, enabling the dynamic creation of quiz content within the application. 


Additional Notes
------------------------------------------------------------------------------------------------------------------------

- Because of its adaptable design, the quiz app ought to function well on a variety of screen sizes.
- Users can use the offered buttons to exit the quiz at any moment or to replay it.
- By altering the questions array in the questions.js file or the CSS styles in the style.css file, developers may quickly personalize the test.
