# react-quiz

# React Quiz

![React Quiz](assets/images/Screenshot%202024-05-23%20155053.png)

A dynamic and interactive quiz application built with React. This project demonstrates how to create a quiz application with React, including state management and component-based architecture.

## Features

- **Dynamic Questions:** Load questions from a JSON file or an API.
- **Interactive UI:** User-friendly interface with responsive design.
- **Score Tracking:** Keep track of user scores and display results at the end of the quiz.
- **Customization:** Easily add or modify questions.

## Screenshots

![Quiz Start](assets/images/Screenshot%20(71).png)
*Quiz Start Screen*

![Quiz Question](assets/images/Screenshot%202024-05-23%20155042.png)
*Quiz Question Screen*

![Quiz Results](assets/images/Screenshot%202024-05-23%20155214.png)
*Quiz Results Screen*

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Shrey0207/react-quiz.git
    cd react-quiz
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Start the development server:**
    ```bash
    npm start
    ```

The application should now be running on `http://localhost:3000`.

## Usage

1. **Starting the Quiz:**
    - Click on the "Start Quiz" button to begin.

2. **Answering Questions:**
    - Select the answer for each question.
    - Click "Next" to proceed to the next question.

3. **Viewing Results:**
    - After the last question, your score and correct answers will be displayed.

## Customization

### Adding/Modifying Questions

Questions are stored in a JSON file (`src/questions.json`). To add or modify questions, update this file with the desired question set. The structure should be as follows:

```json
[
    {
        "question": "What is the capital of France?",
        "options": ["Paris", "London", "Berlin", "Madrid"],
        "answer": "Paris"
    },
    {
        "question": "Which planet is known as the Red Planet?",
        "options": ["Earth", "Mars", "Jupiter", "Saturn"],
        "answer": "Mars"
    }
]
```

### Acknowledgements

- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Create React App](https://create-react-app.dev/): A tool that sets up a modern web app by running one command.
- [OpenAI GPT](https://openai.com/): For providing insights and assistance during the development process.
- [The Ultimate React Course on Udemy](https://example.com/): For the inspiration and learning resources provided.

### Contact

For any inquiries or issues, please contact:

- **Name:** Shrey
- **Email:** [shreytolasaria4297@gmail.com](mailto:shreytolasaria4297@gmail.com)
- **GitHub:** [Shrey0207](https://github.com/Shrey0207)
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/shrey-tolasaria-176381231/)

