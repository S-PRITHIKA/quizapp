 Cute Robot Quiz App

A visually appealing, interactive, and responsive web-based quiz application featuring a cute robot assistant that engages users while they take quizzes. The app is designed to be fun, interactive, and easy to use, with smooth animations, dynamic interactions, and time-bound challenges.

 Features

1. Interactive Quiz Flow

* Step-by-step quiz with multiple-choice questions.
* Dynamic score tracking displayed during the quiz.
* Automatic feedback on selected answers.
* Timer countdown for each question to add challenge.
* End-of-quiz results with total score.

2. Introductory Interaction

* Personalized welcome experience asking for user name.
* Robot interaction with messages based on user choices.
* Scale-based questions to gather user preferences
* Conditional robot responses to user input for an engaging experience.

 3. Robot Assistant

* Animated robot positioned on the screen with:

  * Hopping motion.
  * Waving arm animation.
  * Eye blinking animation.
* Robot provides visual feedback with a floating bubble for:

  * Correct answer messages.
  * Encouragement and hints.
  * Friendly greetings.

4. Animations and UI Enhancements

* Smooth pop-in animation for quiz container.
* Hover effects on answer buttons with scaling and rotation.
* Dynamic color transitions for timer and score display.
* Confetti animation for celebrating quiz completion.

5. Timer and Score System

* 60-second timer for each question with color alerts for low time.
* Score counter updates in real-time.
* Disabled buttons after timer runs out to prevent late answers.

6. Responsive Design

* Mobile-friendly layout that adapts to various screen sizes.
* Robot and bubble repositioning on smaller screens.
* Optimized button sizing for touch interactions.

7. Restart and Start Quiz Controls

* Restart button resets quiz and intro sequence.
* Start button initiates the main quiz after the intro flow.
* Smooth transitions between intro, quiz, and result screens.

8. Accessibility and Usability

* Input focus handling for name entry.
* Keyboard interaction for Enter key submission.
* Clear visual feedback on correct and incorrect answers.

Technologies Used

* HTML5 – Semantic markup for structure
* CSS3 – Advanced styling, animations, gradients, and responsive design
* JavaScript – Quiz logic, timer, score tracking, robot interactions, and confetti animation
* SVG – Custom robot illustration with animations

 Setup and Installation

1. Clone or download the repository:

   git clone 
2. Open the project folder in a code editor or directly in a browser.
3. Open `index.html` in a modern web browser (Chrome, Firefox, Edge, Safari).

 Usage

1. Upon loading the page, the robot introduces itself and asks for your name.
2. Proceed through the interactive intro questions.
3. Click Start Quiz to begin the main quiz.
4. Select answers to each multiple-choice question within the time limit.
5. The robot will provide feedback after each selection.
6. At the end of the quiz, the total score is displayed, along with confetti animation.
7. Click Restart to retake the quiz.

Folder Structure


Cute-Robot-Quiz-App/
│
├─ index.html       # Main HTML file
├─ README.md        # Project documentation
└─ assets/          # Optional folder for images, fonts, or icons



 Customization

* Questions: Modify `questions` array in JavaScript to add, remove, or change quiz questions.
* Intro: Update `introQuestions` array for personalized introduction flow.
* Robot Appearance: Adjust SVG elements and CSS animations for different robot designs.
* Timer & Scoring: Change `timeLeft` variable or scoring logic to modify challenge levels.
* Animations: Modify keyframes in CSS for pop-in, hover effects, robot hop, wave, and confetti.

