# Quiz-Application

observations and learnings

1. Component Structure: Quiz component that manages the quiz functionality, including rendering questions, handling user input, and displaying the result.

2. State Management: React hooks (useState) are used to manage state within the Quiz component, such as tracking the active question, selected answers, and the quiz result.

3. Rendering Questions: Questions are dynamically rendered from the quizQues object, allowing for easy addition or removal of questions without changing the code structure.

4. User Interaction: Radio buttons enable users to select answers for each question, with the selected answer stored in the component's state.

5. Displaying Result: After completing the quiz or clicking "Submit", the user's score and the number of correct and wrong answers are displayed.

6. Resetting Quiz: A function resetQuiz is implemented to reset the quiz state, allowing users to retake the quiz without reloading the page.

7. Styling: Basic CSS styles are applied to improve the visual appearance of the quiz elements.
