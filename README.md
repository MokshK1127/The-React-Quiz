QUIZ APPLICATION

Technologies Used:-

React: The core library used for building the user interface.
JavaScript (ES6+): Utilized for writing the application logic and managing state using React's useReducer and useEffect hooks.
HTML/CSS: For structuring and styling the application components.

Project Functionalities:-
Quiz Application: This project is a React-based quiz application that dynamically fetches questions from a server and presents them to the user.

State Management: The application uses the useReducer hook for state management, handling different states such as loading, error, ready, active, and finished.

Question Navigation: Users can navigate through questions, with the state tracking the current question index and the selected answer.

Scoring System: The application calculates the score based on correct answers and displays the total points earned at the end of the quiz.

Highscore Tracking: The highest score achieved by the user is stored and displayed after the quiz is finished.

Timer: A countdown timer is implemented for the quiz, with a fixed amount of time allocated per question.

Restart Functionality: Users can restart the quiz at any time, which resets the state while preserving the high score.

Error Handling: The application includes basic error handling to manage cases where the quiz questions fail to load.

Progress Tracking: The quiz tracks the user’s progress, showing the current question number, the total number of questions, and the points earned so far.

Responsive UI Components: Components like Header, Main, Footer, Progress, and others are designed to be reusable and responsive.
