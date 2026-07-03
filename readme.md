# Quiz App

A simple, responsive quiz application built using **HTML, CSS, and Vanilla JavaScript**. The app allows users to answer multiple-choice questions, view their score in real time, track quiz progress, and see a personalized result at the end.

## Features

- Interactive multiple-choice quiz
- Real-time score tracking
- Progress bar
- Instant answer feedback
- Final performance message
- Restart quiz functionality
- Responsive design for mobile and desktop
- Built without any external JavaScript libraries

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Project Structure

```
quiz-app/
│
├── index.html      # Main HTML structure
├── styles.css      # Styling and responsive design
├── script.js       # Quiz logic
└── README.md
```

## How It Works

1. Click **Start Quiz**.
2. Read each question and select an answer.
3. Correct answers increase your score.
4. The correct answer is highlighted after each selection.
5. The quiz automatically moves to the next question.
6. After the final question, your score and a performance message are displayed.
7. Click **Restart Quiz** to play again.

## Customization

You can easily customize the quiz by editing the `quizQuestions` array inside `script.js`.

Example:

```javascript
{
  question: "Your question here?",
  answers: [
    { text: "Option A", correct: false },
    { text: "Option B", correct: true },
    { text: "Option C", correct: false },
    { text: "Option D", correct: false }
  ]
}
```

## Learning Concepts

This project demonstrates:

- DOM Manipulation
- Event Listeners
- Arrays and Objects
- Dynamic Element Creation
- Data Attributes (`dataset`)
- Conditional Logic
- CSS Flexbox
- Responsive Web Design

## Future Improvements

- Timer for each question
- Question randomization
- Multiple difficulty levels
- Category selection
- High score storage using Local Storage
- Sound effects and animations
- Dark mode
- Fetch questions from an API

## Getting Started

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Launch `index.html` in your browser.

No installation or dependencies are required.

## License

This project is open source and available under the MIT License.