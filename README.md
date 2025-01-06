# QuizApp 🎯

QuizApp is a **ReactJS-based** web application that allows users to take assessments by solving multiple-choice questions (MCQs). The application ensures a seamless user experience with validations, scoring, and a final result display.

## Features ✨

- **Interactive Quiz**: Users can solve MCQs one question at a time. 📝
- **Option Selection Validation**: Users cannot proceed to the next question without selecting an option. ❌➡️✅
- **Dynamic Scoring**: Scores are calculated in real-time using a `score` state variable. 📊
- **Final Score Display**: After answering the last question, users are presented with their final score. 🏆
- **User-Friendly Interface**: The application provides a smooth and intuitive interface for taking quizzes. 💻

## How It Works ⚙️

1. **Start the Quiz**: 🚀  
   - The quiz begins with the first question displayed on the screen.
   
2. **Option Selection**: 🎯  
   - Users must select an option to enable the "Next" button.  
   - If no option is selected, the user cannot proceed to the next question.

3. **Score Calculation**: 📈  
   - The score is updated dynamically based on the correctness of the selected options.

4. **Final Score**: 🏁  
   - Once the user completes all questions, the application displays the final score out of the total number of questions.

## Technologies Used 🛠️

- **ReactJS**: Frontend framework for building the user interface. ⚛️  
- **State Management**: Managed using React's `useState` and `useEffect` hooks. 🗂️  
- **CSS**: For styling the application. 🎨  

## How to Run the Project 🚀

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/quizapp.git
