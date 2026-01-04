# Free Fire Quiz Panel

## Overview
The Free Fire Quiz Panel is a web application that allows users to create accounts, participate in a quiz related to the game Free Fire, and potentially win redeem codes. The application features a user-friendly interface, a timer for the quiz, and a system to track winners.

## Features
- **Account Creation**: Users can create an account with a username, UID, and password.
- **Quiz Functionality**: The quiz consists of 15 questions (10 easy and 5 difficult) related to Free Fire.
- **Timer**: Users have 2 minutes to complete the quiz. If the time runs out, they are banned from future logins.
- **Score Tracking**: The application tracks the user's score and indicates correct answers with a green light.
- **Redeem Codes**: Users who answer all questions correctly can redeem a code in the format `FF-REDEEM` followed by a four-digit number between 1000 and 3000.
- **Live Winners**: The application displays a list of live winners, allowing only four winners to receive a code.
- **Mobile Responsive**: The quiz page is designed to be visually appealing and functional on mobile devices.

## Project Structure
```
free-fire-quiz-panel
├── index.html
├── src
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   ├── app.js
│   │   ├── auth.js
│   │   ├── quiz.js
│   │   ├── storage.js
│   │   └── ui.js
│   └── data
│       └── questions.js
├── package.json
├── .vscode
│   └── settings.json
└── README.md
```

## Setup Instructions
1. **Clone the Repository**: 
   ```
   git clone <repository-url>
   cd free-fire-quiz-panel
   ```

2. **Install Dependencies**: 
   ```
   npm install
   ```

3. **Open the Application**: 
   Open `index.html` in your web browser to start using the Free Fire Quiz Panel.

## Usage Guidelines
- Create an account using a unique UID.
- Participate in the quiz by answering the questions within the time limit.
- If you win, you will receive a redeem code that can be copied to your clipboard.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.